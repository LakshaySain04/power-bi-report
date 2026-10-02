# Performance Report FY 2027 | Power BI Dashboard

A one-page Power BI dashboard that summarizes e-commerce sales performance for FY 2027. It shows revenue, orders, top products, categories, and cities in one view.

## What's in this repo

| File | Description |
|------|-------------|
| `Report Fy 2027.pbix` | The Power BI report file (open with Power BI Desktop) |
| `dashboard.png` | Screenshot of the dashboard *(add this)* |

## Dashboard Overview

**KPI cards**
- Total Revenue
- Total Orders
- Total Quantity Sold
- Average Order Revenue
- Top Sold Product Value
- Top Sold Category Revenue

**Charts and tables**
- **Top Sold Products**: table of products with their revenue
- **Revenue by Cities**: clustered bar chart
- **Revenue by Category**: donut chart
- **Category vs Revenue**: column chart
- **Price vs Revenue**: line chart showing how revenue changes across price points

## Data

The report uses an e-commerce sales dataset (`harrykart_ecommerce_data`) with these fields:

`Product`, `Category`, `City`, `Quantity`, `Price`, `Revenue`

## DAX Measures Used

- `Total orders`
- `Avg orders Revenue`
- `Top sold product value`
- `Top sold category Revenue`

## Tools

- Power BI Desktop
- DAX

## How to Open

1. Download `Report Fy 2027.pbix`
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Explore the visuals on Page 1

## Author

**Lakshay**
Data Analytics Student | Excel · SQL · Power BI
[LinkedIn](#) · [GitHub](#)
