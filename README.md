# cafe-sales-data-analysis
Cleaned and analyzed 10,000 rows of messy cafe sales data using python, pandas, and Matplotlib.

##Key Insights
-**72, 704** total revenue across 8,159 clean transactions
-**Juice** was the top-selling item at $14,195
-**31.4%** of transactions missing payment method - major data quality issue
-**Flat sales pattern** ~$10.3k/day across all 7 days suggests airport/hospital location

## Tech Stack
Python, pandas, Matplotlib, jupyter Notebook

## Process
1.Diagnosed dataset: 18% missing values, wrong data types, calculation errors
2.Data Cleaning: Handled nulls, standardized formats, removed 1,841 bad rows
3.EDA: Revenue by item, daily trends, payment methods, weekday analysis
4.Exported clean dataset for future use

##VisualiZations
![Sales by Day of Week] (sales_by_day.png)
![Payment Methods] (payment_method.png)
