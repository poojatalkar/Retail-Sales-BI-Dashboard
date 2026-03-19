# Retail-Sales-BI-Dashboard
Retail sales analysis using Python,  Excel, SQL and Power BI

## Project Overview
Analyzed 100K+ retail transactions end to end using Excel, SQL, and Power BI.

## Tools Used
- Excel — Data Cleaning
- PostgreSQL — SQL Analysis
- Power BI — Dashboard
- Python — EDA

## KPIs Developed
- Total Revenue: $143,083,484
- Profit Margin: 40.8%
- Average Order Value: $1,492.65
- Total Orders: 95,859

## Data Cleaning Steps
- Removed 1,000 duplicate orders
- Removed 800 negative quantity rows
- Removed 400 zero price rows
- Fixed 20+ region typos
- Fixed discount scale errors
- Filled 8,079 missing CustomerIDs with UNKNOWN
- Deleted 3,028 missing ProductName rows
- Removed whitespace from ProductName

## SQL Queries
- KPI 1: Total Revenue
- KPI 2: Profit Margin by Category
- KPI 3: MoM Growth using LAG() window function
- KPI 4: AOV using COUNT DISTINCT

## Key Insights
- Revenue showed alternating MoM growth pattern
- Electronics drove highest revenue
- Online channel contributed 42% of total revenue
- 95,859 clean records from 101,000 raw rows
