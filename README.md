# Customer Segmentation & Sales Analysis (Capstone)

## What
A capstone project analysing 3,900 customer transaction records to segment customers by purchasing behaviour and find high-value groups and buying trends.

## How
- **Data:** `customer_shopping.csv` (3,900 records), cleaned version in `customer_shopping_clean.csv`.
- **Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn), MySQL, Power BI.
- **Approach:**
  1. **Clean (Python):** checked nulls, filled missing review ratings with the category median, standardised column names, dropped a duplicate column (promo code used = discount applied).
  2. **Feature engineering:** created age groups (quartile-based) and a purchase frequency in days column.
  3. **Analyse (SQL):** 10 business queries, for example revenue by gender, discount use vs spend, subscribers vs non-subscribers, New / Returning / Loyal customer segments, top products per category, revenue by age group.
  4. **Visualise (Power BI):** customer shopping dashboard.

## Impact / Results
- Customers grouped into New, Returning and Loyal segments to show high-value groups.
- Answers business questions on discounts, subscriptions, shipping type and product ratings.

## Files
- `Capstone_Customer_shopping.ipynb`: Python cleaning and EDA
- `Capstone Customer Shopping.sql`: SQL analysis
- `Customer shopping dashboard.pbix`: Power BI dashboard
- `Mdd Customer Shopping Analysis Capstone Project.pdf`: project report
