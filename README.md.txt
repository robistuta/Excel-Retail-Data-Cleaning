# Excel Retail Data Cleaning and Sales Dashboard

## Project Overview

This project demonstrates data cleaning, data quality assessment,
sales analysis, and dashboard development using Microsoft Excel 2013.

I analyzed a sample of 10,000 transaction rows from the
UCI Online Retail dataset.

After cleaning, 9,658 valid sales rows remained.

The project includes:
- Before-and-after data quality assessment
- Data cleaning using Excel
- Sales analysis using PivotTables
- KPI calculations
- Sales dashboard with charts
- Documentation of cleaning decisions

## Tools and Skills

**Tool:** Microsoft Excel 2013

**Skills demonstrated:**
- Data cleaning
- Duplicate removal
- Missing-value analysis
- Data validation
- Excel formulas
- PivotTables
- Sales analysis
- KPI reporting
- Dashboard development
- Data visualization

## Dataset

**Source:** UCI Machine Learning Repository

**Dataset:** Online Retail

**Dataset link:**
https://archive.ics.uci.edu/dataset/352/online+retail

The original dataset contains approximately 541,909 rows.

This project uses the first 10,000 transaction rows.

The analyzed sample covers December 2010.

## Data Cleaning Results

| Data Quality Metric | Before | After |
|---|---:|---:|
| Total Records | 10,000 | 9,658 |
| Missing Customer IDs | 2,291 | 2,246 |
| Missing Descriptions | 42 | 0 |
| Cancelled Transaction Rows | 100 | 0 |
| Invalid Quantities | 130 | 0 |
| Invalid Prices | 46 | 0 |
| Duplicate Rows | 196 | 0 |

**342 rows removed (3.42%).**

**9,658 rows retained (96.58%).**

Missing Customer IDs were retained because these records
could still represent valid sales.

## Sales Performance KPIs

| KPI | Result |
|---|---:|
| Total Sales | £183,529.13 |
| Total Units Sold | 89,371 |
| Unique Invoices | 424 |
| Average Sales per Invoice | £432.85 |
| Average Sales per Transaction Row | £19.00 |

## Key Business Insights

### 1. Sales by Country

The United Kingdom generated **£167,651.80**,
representing approximately **91.35%** of total sales.

### 2. Highest-Revenue Product

**REGENCY CAKESTAND 3 TIER**

Sales: **£7,717.95**

### 3. Highest-Volume Product

**WORLD WAR 2 GLIDERS ASSTD DESIGNS**

Units sold: **3,409**

### 4. Monthly Sales

The sample covers **December 2010**.

Total sales: **£183,529.13**.

Because the sample contains only one month,
monthly sales comparisons were not possible.

## Sales Dashboard

The dashboard contains:

- Total Sales KPI
- Total Units Sold KPI
- Unique Invoices KPI
- Average Sales per Invoice KPI
- Top 10 Products by Sales chart
- Top 10 Products by Quantity chart
- Sales by Country chart

![Retail Sales Dashboard](screenshots/sales_dashboard.png)

## Before and After Cleaning

### Before Cleaning

![Before Cleaning](screenshots/before_cleaning.png)

### After Cleaning

![After Cleaning](screenshots/after_cleaning.png)

## Project Files

- [Excel Workbook](workbook/Retail_Data_Cleaning.xlsx)
- [Data Cleaning Report](reports/data_cleaning_report.md)
- [Dataset Source](data/dataset_source.md)

## Limitations

- Only 10,000 rows from the original dataset were analyzed.
- The sample covers December 2010 only.
- Cancelled transactions were excluded.
- Sales represent positive sales, not net revenue after returns.
- Missing Customer IDs were retained.

## Conclusion

This project demonstrates how Excel can be used to transform
raw retail transaction data into a cleaned dataset,
analyze business performance, and create a sales dashboard.

The project highlights practical Data Analyst skills in
data preparation, analysis, visualization, and reporting.