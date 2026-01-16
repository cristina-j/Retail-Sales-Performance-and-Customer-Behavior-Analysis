# Sales & Customer Performance Dashboard Analysis

## Overview
This project analyzes sales performance and customer purchasing behavior for a fictional retail business using transactional sales data from 2011–2016. The analysis is 
presented through an interactive Tableau dashboard.

**Note**: Due to limitations in the dataset, customer analysis is performed at the order level rather than the individual customer level.

---

## Business Problem
The business is a retail company selling consumer products across multiple categories and subcategories in the U.S. and Europe. The company wants to better understand:

- How the business is performing year-over-year
- What is driving revenue and profit growth
- How customer purchasing behavior is changing over time
- Which customer segments contribute most to revenue

**Note**: The dataset does not include unique customer identifiers, which limits the ability to perform true customer-level analysis such as retention or lifetime value.

---

## Proposed Solution
To address these challenges, I built two interactive Tableau dashboards to visualize the data:

### 1. Sales Dashboard
Focused on overall business performance:
- Total Revenue (YoY comparison)
- Total Profit (YoY comparison)
- Total Orders / Order Quantity
- Revenue and Profit trends over time
- Revenue and Profit by product subcategory

### 2. Customer Dashboard
Focused on customer behavior:
- Total Orders
- Average Order Value (AOV)
- Revenue and Profit (context metrics)
- Orders and revenue by age group and gender
- Year-over-year comparisons of customer behavior metrics

Key design decisions:
- Customer metrics are analyzed at the order level
- Metrics such as total customers, retention, and CLV are intentionally excluded
- Year-over-year metrics are parameter-driven for dynamic analysis

---

## Results & Key Insights

### Sales Performance
- Revenue and profit increased significantly in 2015 despite a decline in total order volume
- Profit growth closely followed revenue growth, suggesting healthy margins
- Revenue gains were concentrated in a small number of high-performing product subcategories

### Customer Behavior
- Total orders declined year-over-year, but Average Order Value (AOV) increased sharply
- Revenue growth was driven by higher-value purchases, not increased order frequency
- Adult and young adult age groups contributed the largest share of revenue
- Revenue distribution across genders remained relatively balanced

### Data Considerations
- The dataset contains incomplete records for the final five months of 2014 and 2016.
- No data was attributed; all insights are based on available records only.
- External economic context was reviewed to support interpretation, not to explain missing data.

---

## Business Recommendations
Based on the analysis:

- The business should focus growth strategies on increasing order value, as customers are spending more per purchase
- The business should prioritize high-performing product subcategories that consistently drive revenue and profit such as the Mountain bikes.
- THe business should target marketing efforts toward core revenue-driving age groups so they are more prone to continue purchasing their products.

---

## Insight At a Glance
<img width="2038" height="1200" alt="Sales   Profits Trend Over Time" src="https://github.com/user-attachments/assets/3ede9d5d-5ba4-4c6b-b570-d802341270d1" />

