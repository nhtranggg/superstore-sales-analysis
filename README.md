# Superstore Sales Analysis

Superstore sales dashboard built in both Microsoft Excel and Power BI — comparing tool approaches on the same dataset to demonstrate cross-platform BI skills.

## Overview
This project analyzes $993M in sales data across 4 regions and 3 product categories, built twice using different tools: Excel (pivot tables, dynamic formulas) and Power BI (DAX measures, interactive visuals). The two versions take complementary analytical angles — the Excel dashboard visualizes sales chronologically across quarters to reveal long-term trend, while the Power BI dashboard groups quarters across years to reveal seasonality patterns within each quarter. The Power BI version also extends the analysis further with city-level and product-level breakdowns, plus a custom Calendar table for accurate YoY growth calculations.

## Business Questions
- Which regions and categories drive the most sales, and how concentrated is that dependency?
- How has overall sales grown year over year? *(Excel)*
- Is there a recurring seasonal pattern across quarters, and which spikes are isolated events versus true seasonality? *(Power BI)*
- What are the top-performing cities and products? *(Power BI)*
- Is year-over-year growth accelerating or decelerating, and what might explain the trend?

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
- **West region** leads in sales, followed by Central, East, and South — likely driven by a denser network of high-revenue cities (Houston, Los Angeles, San Francisco all rank in the top 5). Worth investigating whether this is city-density advantage or a true regional preference, to decide if the same playbook can lift underperforming regions.
- **Furniture** dominates revenue at **~$512M (51.53%)**, with Technology (27.65%) and Office Supplies (20.82%) splitting the remainder — this concentration in a single category is a potential risk if Furniture demand softens, and warrants monitoring category diversification over time.
- Total sales grew steadily year over year — $186M (2015) → $218M (2016) → $275M (2017) → $314M (2018) — indicating consistent overall business growth across the period
- **Q1 is consistently the weakest quarter across all 4 years**, followed by a rebound in Q2 — this is a genuine recurring seasonal pattern (unlike the Q3-2017 spike below), suggesting Q1 demand softness should be planned for (e.g., through promotions or inventory adjustments) rather than treated as inventory risk
- **Q3-2017 stands out with a sharp spike to $103M**, well above the surrounding quarters (Q2-2017: $54M, Q4-2017: $86M) — without a similar spike in Q3 of other years, this looks like an isolated event in 2017 rather than a recurring seasonal pattern. Forecasting should not assume this surge will repeat.
- **YoY growth accelerated then decelerated** — 17.08% (2016) → 25.96% (2017) → 14.13% (2018) — the 2017 peak coincides with the Q3-2017 spike, suggesting that year's growth may have been partly driven by this isolated event rather than sustained momentum. The 2018 slowdown could reflect a return to baseline, worth investigating further.

## Files
- `Excel version/Excel dashboard.pdf` — Excel dashboard export (PDF)
- `Excel version/Excel dashboard.png` — Excel dashboard export (image)
- `Excel version/Superstore Sales dataset.xlsx` — Source data and Excel dashboard
- `Power BI version/Power BI dashboard.pdf` — Power BI dashboard export (PDF)
- `Power BI version/Power BI dashboard.png` — Power BI dashboard export (image)
- `Power BI version/Superstore Sales dashboard.pbix` — Power BI dashboard file
