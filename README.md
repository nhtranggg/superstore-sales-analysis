# Superstore Sales Analysis

Superstore sales dashboard built in both Microsoft Excel and Power BI — comparing tool approaches on the same dataset to demonstrate cross-platform BI skills.

## Overview
This project analyzes $993M in sales data across 4 regions and 3 product categories, built twice using different tools: Excel (pivot tables, dynamic formulas) and Power BI (DAX measures, interactive visuals). The two versions take complementary analytical angles — the Excel dashboard visualizes sales chronologically across quarters to reveal long-term trend, while the Power BI dashboard groups quarters across years to reveal seasonality patterns within each quarter. The Power BI version also extends the analysis further with city-level and product-level breakdowns, plus a custom Calendar table for accurate YoY growth calculations.

## Business Questions
- Which regions and categories drive the most sales?
- How has overall sales trended chronologically across years and quarters? *(Excel)*
- Does any quarter consistently outperform others across years, revealing a seasonal pattern? *(Power BI)*
- What are the top-performing cities and products? *(Power BI)*
- What is the year-over-year growth trend?

## Tools & Skills

### Excel Version
- Dynamic formulas and pivot tables
- KPI cards (Total Sales, Top Region, Top Category, YoY Growth)
- Region and Year slicers with real-time updates

### Power BI Version
- DAX measures including a custom Calendar table and DATEADD-based YoY Growth calculation
- Top 10 Cities and Top 10 Products breakdown
- Interactive Region and Year filtering

## Dashboard Preview

### Excel Version
![Excel Dashboard](Excel%20version/Excel%20dashboard.png)

### Power BI Version
![Power BI Dashboard](Power%20BI%20version/Power%20BI%20dashboard.png)

## Key Insights
- West region leads in sales, followed by Central, East, and South
- Furniture is the top-performing category, generating ~$512M (51.53%) of total sales
- The Excel trend view shows overall sales growing across years, with a sharp Q4-2015 spike followed by steadier growth into 2018
- The Power BI quarter-comparison view shows a sharp Q3-2017 spike that stands out from otherwise steady performance across quarters — likely a one-time event worth investigating rather than a recurring seasonal pattern
- YoY growth reached 14.13% in the most recent year-over-year comparison

## Files
- `Excel version/Excel dashboard.pdf` — Excel dashboard export (PDF)
- `Excel version/Excel dashboard.png` — Excel dashboard export (image)
- `Excel version/Superstore Sales dataset.xlsx` — Source data and Excel dashboard
- `Power BI version/Power BI dashboard.pdf` — Power BI dashboard export (PDF)
- `Power BI version/Power BI dashboard.png` — Power BI dashboard export (image)
- `Power BI version/Superstore Sales dashboard.pbix` — Power BI dashboard file
