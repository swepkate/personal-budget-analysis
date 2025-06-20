# Personal Budget Analysis

This project is designed for analyzing and visualizing personal financial data based on transaction history exported from a bank account.  
It enables classification of expenses, creating category-based charts, and predicting future spending.

---

## Dataset Columns

- **Transaction Date and Time** — date and time of the transaction (object)  
- **Transaction Amount** — amount of the transaction (float64)  
- **Transaction Description** — description of the payment (object)  
- **Card Number** — card number used for the transaction (object)  
- **Date** — date of the transaction (object)  
- **Category** — expense/income category (object)  
- **Subcategory** — more detailed category (object)  

---

## Data Source

The transaction history is exported from the personal bank account in table format (usually PDF), you can convert a PDF to Word and then add it to Excel.

---

## What has been done in this project

1. Loaded transaction data.  
2. Manually labeled categories and subcategories for expenses.  
3. Checked for missing values — none found.  
4. Performed data analysis: created charts, explored categories and trends.  
5. Built a RandomForestRegressor model to predict next month’s spending.  
6. Built a RandomForestClassifier model to predict expense categories, achieving an accuracy of 0.8053.  
7. Used Plotly Express for data visualization to create interactive and clear charts.

---

## Installation

```bash
git clone https://github.com/swepkate/personal-budget-analysis.git
cd personal-budget-analysis
pip install -r requirements.txt
