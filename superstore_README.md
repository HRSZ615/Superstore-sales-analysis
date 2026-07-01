# Superstore Sales Analysis

## Overview
This project analyzes retail sales data from a fictional Superstore using Python and pandas. The goal was to uncover category performance trends, regional sales patterns, customer segment behavior, and seasonal demand shifts — the kind of analysis a business analyst would perform to inform inventory, marketing, and operational decisions.

## Dataset
- **Source:** [Superstore Sales Dataset — Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
- **Coverage:** Transaction-level sales data from 2015 to 2018
- **Tool:** Python (pandas) · Google Colab

## Skills Demonstrated
- Loading and exploring datasets with pandas
- Data cleaning and date parsing with `pd.to_datetime`
- Filtering and conditional selection
- GroupBy aggregations across multiple dimensions
- Time-series trend analysis by year and month
- Deriving business insights from raw sales data

## Analysis Summary

### Query 1 — Total Sales by Category
Technology led all three categories with $827,455 in total sales, followed by Furniture and Office Supplies. The store should target local offices with bundled technology and office supply offerings to grow the two lower-performing categories.

### Query 2 — Top 10 States by Sales
California dominated with $446,306 in sales — nearly 50% more than second-place New York at $306,361. Lower-performing states like Virginia and Ohio represent growth opportunities, particularly through technology product expansion.

### Query 3 — Sales by Customer Segment
The Consumer segment generated $1,148,060 — more than Corporate and Home Office combined. Targeted marketing of office supplies and technology to Corporate buyers, and furniture to Home Office customers, could significantly close the gap.

### Query 4 — Monthly Sales Trend
Sales spiked consistently in November and December across all four years, confirming strong holiday-season demand. A summer slump in June–August was also identified, suggesting an opportunity for seasonal product promotions in slower months.

### Query 5 — Top 10 Best Selling Products
The Canon imageCLASS 2200 Advanced Copier led all products at $61,599 in sales — nearly double the second-place product. All top 10 products are office-oriented, confirming that professional buyers are the store's most valuable customers.

### Query 6 — Sales by Region
The West region led with $710,219 in sales, driven by its concentration of tech companies and professionals. The Central and South regions underperformed and represent growth opportunities through regionally targeted inventory — for example, prioritizing furniture in Central markets.

## Files
- `superstore_sales_analysis.ipynb` — Full analysis notebook with code and outputs

## Author
Business Analytics Student — Farmingdale State College
Self-directed Python learning project, Summer 2026
