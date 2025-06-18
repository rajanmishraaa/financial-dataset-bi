# Financial Performance Dashboard

## Overview
This Power BI dashboard provides a clean summary of financial performance based on a structured dataset. It includes core financial KPIs, a profit trend over time, and sales breakdowns by both product and customer segment.

## Dataset
- **Source:** Financial_Dataset.csv
- **Records:** 730
- **Key Fields:** Date, Product, Segment, Gross Sales, Net Sales, Profit, Units Sold

## Tools Used
- Power BI Desktop
- DAX (for calculated measures)
- CSV file (pre-cleaned data)

## Dashboard Components

| Section                | Visual Type       | Description |
|------------------------|-------------------|-------------|
| KPI Overview           | Card Visuals      | Displays overall Gross Sales, Net Sales, Profit, and Units Sold |
| Profit Trend           | Line Chart        | Shows profit values across the selected time period |
| Sales by Product       | Bar Chart         | Visual representation of total sales per product |
| Sales by Segment       | Donut Chart       | Displays total sales categorized by customer segments |
| Date Range Filter      | Slicer            | Filters all visuals based on selected date range |

## Development Process
1. Started with a cleaned CSV file containing sales and financial data.
2. Imported the dataset into Power BI and structured the data model.
3. Built custom DAX measures for key performance indicators.
4. Designed visuals for both high-level metrics and category-based breakdowns.
5. Applied filters and interactivity for exploratory analysis.

## Files Included
- `Financial_Dataset.csv` – The data used to build the dashboard
- `Dashboard - Financial Report Summary.pbix` – Power BI dashboard file
- `README.md` – Project documentation

## Purpose
This project demonstrates the ability to create structured, professional dashboards using Power BI. It reflects key skills in data modeling, metric calculation, and report design focused on financial data visualization.
