# MIS Performance Dashboard (Excel)

A simple Excel MIS dashboard that turns employee-level business data into KPIs and charts for management.

## Project Overview
This project uses 30 employee records (Jan-May) covering orders, revenue, targets, actual sales, returns and complaints. The data is cleaned, analysed and shown on a one-page dashboard.

## Workbook Structure (3 Sheets)

| Sheet | Purpose |
|-------|---------|
| **MIS_Data** | Raw data in an Excel Table, plus 4 calculated columns |
| **MIS_Analysis** | Summary tables and data-quality checks that feed the charts |
| **MIS_Dashboard** | KPI cards, filters, charts and an employee detail table |

## Calculated Columns (MIS_Data)
- **Achievement %** = Actual_Sales / Target
- **Target Status** = "Target Achieved" or "Target Not Achieved"
- **Return Rate** = Returns / Orders
- **Performance** = Excellent (100% or more), Good (90% to below 100%), Needs Improvement (below 90%)

## Dashboard Features
- **6 KPI cards:** Total Revenue, Actual Sales, Orders, Average Achievement %, Returns, Complaints
- **5 charts:**
  - Monthly Revenue
  - Actual Sales vs Target
  - Revenue by City
  - Achievement % by Department
  - Employee Performance (doughnut)
- **4 drop-down filters:** Department, City, Month, Channel
- **Employee detail table** with conditional formatting on Achievement % (green, amber, red)

## Skills Demonstrated
- Excel Tables and structured references
- Formulas: SUMIFS, AVERAGEIFS, COUNTIFS, COUNTIF, IF, INDEX, SUMPRODUCT
- Data cleaning and validation checks (duplicates, blanks, data types)
- Conditional formatting
- Data validation drop-downs
- KPI cards and dashboard design

## How It Works
1. Raw data is stored in the `MIS_Data` table.
2. `MIS_Analysis` summarises it by month, city, department, channel and performance.
3. `MIS_Dashboard` shows the results as KPIs and charts for management.

## How to Use
1. Download and open `MIS_Executive_Dashboard.xlsx`.
2. Go to the **MIS_Dashboard** sheet.
3. Use the yellow drop-downs to filter. Set them back to "All" to reset.

## Notes
- All data is sample data created for practice.
- The analysis tables are formula-based (SUMIFS / AVERAGEIFS / COUNTIFS). They can also be built as PivotTables with slicers in Excel.

## Tools Used
Microsoft Excel
