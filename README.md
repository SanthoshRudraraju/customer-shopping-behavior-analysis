# Customer Shopping Behavior Analysis

End-to-end analysis of 3,900 retail transactions using Python, PostgreSQL, and Power BI.

## Overview
This project analyzes customer shopping behavior to uncover spending patterns, customer segments, and subscription trends, and turns the findings into business recommendations.

## Tools Used
- **Python** (pandas): data cleaning and feature engineering
- **PostgreSQL**: business analysis with SQL
- **Power BI**: interactive dashboard

## Dataset
- 3,900 transactions, 18 columns
- Covers customer demographics, purchase details, discounts, subscription status, and review ratings


## Workflow
1. **Data cleaning (Python):** filled 37 missing review ratings with the category median, renamed columns to snake_case, created `age_group` and `purchase_frequency_days`, and dropped the redundant `promo_code_used` column.
2. **SQL analysis:** wrote 10 queries covering revenue by gender and age group, discount-dependent products, subscriber vs. non-subscriber spend, customer segmentation, and top products per category.
3. **Dashboard (Power BI):** built an interactive dashboard with KPIs and filters for subscription status, gender, category, and shipping type.

## Key Insights
- Male customers generated about 68% of total revenue.
- Subscribers (27% of customers) spend about the same per order as non-subscribers ($59.49 vs $59.87).
- About 80% of customers fall in the "Loyal" segment.
- Clothing is the top category by revenue.

## Recommendations
- Promote exclusive subscriber benefits
- Build loyalty rewards for repeat buyers
- Review discount policy to protect margins
- Focus marketing on high-revenue age groups


## Repository Structure
- `Customer_Shopping_Behavior_Analysis.ipynb`: Python notebook
- `customer_behavior_sql_queries.sql`: SQL queries
- `customer_behavior_dashboard.pbix`: Power BI file
- `images/`: dashboard screenshots


## Author
Santhosh Varma Rudraraju | santhoshvarma2004@gmail.com
