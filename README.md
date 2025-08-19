# Task-6-Sales-Data-Analysis
Sales trend analysis using sql aggregations.

# Sales Trend Analysis Using Aggregations

## Project Overview
Analyzed monthly revenue and order volume from the `online_sales` dataset using SQL.

## Files
- `online_sales.csv` — sales dataset  
- `sales_data.sql` — SQL script for trend analysis  

## Key Points
- Used `EXTRACT(MONTH/YEAR FROM order_date)` for time grouping  
- Calculated monthly revenue with `SUM(amount)`  
- Calculated order volume with `COUNT(DISTINCT order_id)`  
- Applied `GROUP BY` and `ORDER BY` for aggregation and sorting  

## Outcome
Learned how to group sales data by month/year and identify top-performing months.
