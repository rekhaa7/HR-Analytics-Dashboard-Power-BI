# HR Analytics Dashboard (Power BI)

## Overview
This is an end-to-end HR Analytics dashboard built in Microsoft Power BI. It provides actionable insights into workforce demographics, promotion eligibility, retrenchment risks, employee tenure, job levels, department performance, job satisfaction, and more.

## Data Preparation (Power Query)
- Thorough data cleaning (handled nulls, duplicates, inconsistent formatting,)
- Added calculated columns:
  - Tenure categories (Early Tenure, etc.)
  - Promotion Status
  - Retrenchment
  - Service Year
  - Other supporting columns as needed

## Measures & DAX
Created multiple custom measures for:
- Accurate percentages (e.g., gender ratio, promotion %, retrenchment %)
- Dynamic counts (due for promotion, not due, active workers)
- Conditional formatting and tooltips

## Tools Used
- Microsoft Power BI Desktop
- Power Query (for data transformation)
- DAX (for measures and calculations)

## How to Use
1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Refresh data if using your own dataset (current version uses the cleaned HR dataset)
