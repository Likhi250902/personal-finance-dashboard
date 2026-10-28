# Personal-finance-dashboard
An interactive Excel dashboard that analyses personal bank and credit-card transactions to show where money comes from, where it goes, and how much is saved each month.

![Dashboard](https://github.com/Likhi250902/personal-finance-dashboard/blob/main/dashboard_image1.png)
![Dashboard](https://github.com/Likhi250902/personal-finance-dashboard/blob/main/dashboard_image2.png)

## Dataset
- Source: [Personal Transactions dataset on Kaggle](https://www.kaggle.com/datasets/uom220338n/personal-finance-dataset?select=personal_transactions_dashboard_ready+%282%29.xlsx)
- License: Dataset licensed under the MIT License. 
- Raw file: [Raw_data](https://github.com/Likhi250902/personal-finance-dashboard/blob/main/Raw_Data.xlsx), the original file as downloaded from Kaggle
- 806 transactions, Jan 2018 – Sep 2019
- Columns: Date, Description, Amount, Transaction Type, Category, Account Name, Month
- Amounts are in Indian Rupees (₹)
- Used here for learning and portfolio purposes

## Key Definitions
- Income: credits categorised as Paycheck
- Expense: debits, excluding Credit Card Payments (transfers, to avoid double counting)
- Net Savings: Income − Expense

## What's Inside
- KPI cards: Total Income, Total Spending, Net Savings, Savings Rate, Average Monthly Spend, Top Category
- Charts: Monthly Income vs Expense, Monthly Net Savings, Top 10 Expense Categories, Expense % by Account
- Pivot tables, pivot charts for filtering by Month, Category and Account

## Key Insights
- Income of ₹93,750 against Expense of ₹63,042 gives a savings rate of about 32.8%
- Mortgage & Rent is the largest spending category, followed by Home Improvement
- Expenses spikes in May 2018 and June 2019 are one-off purchases, not a trend
- About 78% of Expense goes through the Checking account

## How to Use
1. Download https://github.com/Likhi250902/personal-finance-dashboard/blob/main/personal_finance_dashboard.xlsx
2. Open the Dashboard sheet to view the KPIs and charts
3. The Data sheet holds the transactions and the Calcilations sheet holds the summary tables
4. To update, add new rows to the Data sheet; the dashboard recalculates automatically

## Limitations
- Only 21 months of data, with no budget targets
- Savings rate is sensitive to large one-off purchases
- No interactive filters; the dashboard shows the full period


## Author
Likhitha Tervati: [LinkedIn](https://www.linkedin.com/in/likhitha-tervati-7383a7294/)

