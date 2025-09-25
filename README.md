# Dashboard Design Tableau

## Overview
Interactive dashboard built with Tableau (Superstore / sales dataset).  
Covers: KPIs (Sales, Profit, Growth), time-series, category & geographic analysis, segmentation, and business recommendations.

## Files
- `data/SalesFinancial.csv` – raw dataset
- `workbook/SalesFinancial.twbx` – Tableau packaged workbook
- `exports/Dashboard.pdf` – exported dashboard PDF

## How to open
1. Install Tableau Public / Desktop.
2. Open `workbook/SalesFinancial.twbx` in Tableau.
3. Interact with filters (Region, Year, Category), use navigation buttons at top.

## How I built it
- Data cleaning: parsed dates, removed duplicates, handled missing values, created `wait_days`, computed KPIs.
- Visuals: KPI row, Sales trend, Category performance, Map by State, Segment analysis, Top customers scatter.
- Interactivity: Filters (Region, Year), highlight & filter actions, navigation buttons.

## How to reproduce
- Open `data/SalesFinancial.csv` in Tableau.
- Create calculated fields (see submission.md).
- Build sheets as labeled and assemble dashboard.
