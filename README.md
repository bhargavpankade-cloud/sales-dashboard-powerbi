# Sales Performance Dashboard — Power BI Project

## Overview
An interactive business intelligence dashboard analyzing retail sales
performance using the Superstore Sales dataset with 40 orders across
multiple regions, categories and customer segments.

## Tools Used
- Power BI Desktop
- Power Query — data cleaning and transformation
- DAX — calculated measures and KPIs

## Dataset
Superstore Sales dataset
40 orders with columns: Sales, Profit, Discount, Region,
Category, Sub-Category, Customer Name, Order Date

## DAX Measures Created
| Measure | Formula |
|---|---|
| Total Sales | SUM of all sales values |
| Total Profit | SUM of all profit values |
| Profit Margin | Total Profit divided by Total Sales |
| Total Orders | COUNTROWS of orders table |
| Avg Discount | AVERAGE of discount column |

## Dashboard Visuals
1. KPI Cards — Total Sales, Total Profit, Profit Margin, Total Orders
2. Line Chart — Monthly sales trend by category
3. Bar Chart — Sub-category profit ranking
4. Donut Chart — Region wise sales breakdown
5. Scatter Plot — Discount vs Profit margin analysis
6. Slicers — Region, Category and Date range filters

## Key Business Insights
- Technology category has highest sales but profit is affected by discounts
- Bookcases and Fasteners are loss making products due to heavy discounting
- High discounts above 30 percent directly result in negative profit margin
- South region has highest number of orders

## How to Open
1. Download Power BI Desktop free from microsoft.com
2. Download the Sales_Performance_Dashboard.pbix file
3. Open the file in Power BI Desktop
4. All visuals and DAX measures load automatically
