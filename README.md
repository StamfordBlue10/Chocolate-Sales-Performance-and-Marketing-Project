# Chocolate-Sales-Performance-and-Marketing-Efficiency-Project
This project analyzes chocolate sales performance and marketing efficiency over a 24-month period. This analysis examines sales trends, regional partitions, order value and the relationship between marketing expenditure and revenue. 

## Business Questions

This project seeks to answer:

1. How sales performance change over time?
2. What season/quarter did sales best performed?
3. Which regions contribute most significantly to revenue?
4. What is the typical revenue generated per order?
5. How effective is marketing and does increased marketing corresponds to increase revenue?
6. Which factors affect increase revenue? Quantity of boxes sold or high-value orders?

## Tools used

- MS Excel
- Power Query
- PivotTables
- Data Cleaning

## Data Cleaning & Preparation

- Corrected amount calculations to improve consistency and accuracy.
- Corrected negative values in Boxes Sold column using absolute value (based on assumption that negative values are data-entry errors)
- Applied discounts on revenue for accurate analysis
- Added period and quarter columns to support time-based analysis
- Filled missing price per box prices by averages (grouped by Product, Country, Channel) using Power Query
- Standardized mixed date formats
- Excluded approximately 500 records with missing order dates because they could not be reliably assigned to monthly or quarterly periods.
- Identified missing values in the Marketing Spend column and retained them as null because the actual expenditure could not be verified.


## Key KPIs

- Revenue -  $103.6M
- Orders - 199,563
- AOV (Average Order Value) - $519.08
- Boxes sold - 28.4M
- Marketing Spend - $19.0M
- ROAS (Return on Ad Spend) - 5.45x

AOV = Revenue after discount / Orders
ROAS = Revenue after discount / Marketing Spend
  
## Key Insights

### Q4 2023 was the strongest quarter

Q4 2023 recorded the highest quarterly revenue with a 14.18% increase compared from the previous quarter during the
24-month period, driven primarily by high order volume and higher AOV.

### December 2023 was the strongest month

December 2023 led in revenue, boxes sold, and AOV.

Australia and Brazil contributed 77.15% of December 2023 revenue.

### Australia and Brazil takes the majority portion of total revenue

Summing the two regions would show 77.1% of total sales across the 24-month period. Along with high value orders.

### June 2022 showed the weakest performance

June 2022 recorded the lowest revenue and boxes sold, while
its AOV was also among the lowest across the 24-month period.

### Recommendations

- Investigate the factors behind Q2 2022 and Q2 2023 massive decline in all aspects.
- Investigate February's recurring decline and compare it against months in the same quarter. This could determine whether it is a seasonal occurrence and identify potential opportunities to relieve weaker sales.
- Look at both Australia and Brazil's strong December 2023 performance and decide whether successful strategies can be replicated in other periods.

### February showed consistent weaker performance

February 2022 and February 2023 both experienced substantial declines in revenue and quantity of boxes sold across all chocolate categories combines with lower AOV. This pattern may be showing a sign of recurring decline period of weaker sales performance.


## Dashboard

<img width="1015" height="522" alt="image" src="https://github.com/user-attachments/assets/ea5bf194-ac45-4d16-92cd-76e42b03ef90" />

