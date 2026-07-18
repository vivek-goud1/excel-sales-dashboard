# Superstore Sales Dashboard (Excel)

An interactive Excel dashboard built on a synthetic Superstore-style retail dataset (1,800 orders, FY2023–FY2024), designed to practice real-world sales/BI reporting skills.

## What it does

- **KPI cards**: Total Sales, Total Profit, Total Orders, Profit Margin — all update live based on the selected region
- **Region filter**: a dropdown control that dynamically filters every KPI and chart on the dashboard
- **Monthly Sales & Profit Trend**: line chart across 24 months
- **Sales by Category**: bar chart (Furniture, Office Supplies, Technology)
- **Sales by Segment**: pie chart (Consumer, Corporate, Home Office)
- **Top 10 Sub-Categories by Sales**: ranked bar chart
- **Sales & Profit by Region**: comparison bar chart across all four regions

## How it's built

- `Data` sheet: raw transactional data (Order ID, dates, region, category, sub-category, product, segment, sales, profit, discount, etc.)
- `Summary` sheet: calculation tables built entirely with live formulas (`SUMPRODUCT`, `SUMIFS`, `INDEX`, `MATCH`, `LARGE`) — no hardcoded numbers, so every chart recalculates when the region filter changes
- `Dashboard` sheet: the KPI cards, filter control, and all charts, laid out for a single-screen view

## Skills demonstrated

- Excel formulas for dynamic, filter-driven reporting (SUMPRODUCT/SUMIFS-based conditional aggregation)
- Data validation (dropdown filter control)
- Chart building: line, column, pie, and bar charts linked to formula-driven data tables
- Dashboard layout and formatting (KPI cards, consistent color scheme, single-font styling)

## Files

- `Superstore_Sales_Dashboard.xlsx` — the full workbook

## Note on the data

The dataset is synthetically generated to resemble a real Superstore-style retail dataset (realistic order dates, regions, categories, pricing, and discount patterns) for the purpose of building and practicing this dashboard.
