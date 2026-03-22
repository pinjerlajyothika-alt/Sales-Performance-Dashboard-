# 📋 Data Folder

This folder contains the raw source data used in this project.

## Files

| File | Description |
|------|-------------|
| `orders_data.xlsx` | Original AdventureWorks dataset — 4 tables, 60,405 raw rows before cleaning |

## About the Data

| Table | Rows | Description |
|-------|------|-------------|
| fact_InternetSales | 60,405 | All sales transactions — central fact table |
| dim_Product | 606 | Product catalogue with names, costs, categories |
| dim_Customer | 18,484 | Customer demographics, income, education, occupation |
| dim_SalesTeritory | 11 | Sales regions, countries and territory groups |

## Data Problems Found (Before Cleaning)
- Date columns stored as 8-digit numbers (20130415 instead of proper dates)
- 6 null rows with missing sales data
- No Product Category column existed
- No Income Bracket column existed
- Income Bracket sorted alphabetically incorrectly

## Data After Cleaning
- 60,399 clean rows (6 nulls removed)
- Proper Date columns created (OrderDate, ShipDate, DueDate)
- Product Category column created using DAX
- Income Bracket column created and sorted correctly
```

7. Scroll down
8. In commit message type:
```
Add Data folder with README explaining source data
```
9. Click **"Commit new file"** ✅

---

### Create a "Documentation" Folder

1. Click **"Add file"**
2. Click **"Create new file"**
3. Type in filename box:
```
Documentation/README.md
# 📄 Documentation Folder

This folder contains all project documentation files.

## Files

| File | Description |
|------|-------------|
| `SalesPerformanceDashboard_Documentation.docx` | Complete 32-page methodology document |
| `SalesPerformanceDashboard_Presentation.pptx` | 12-slide professional project presentation |

## What the Documentation Covers

### Methodology Document (32 pages)
- Project background and objectives
- Dataset description — all 4 tables explained
- Step by step data cleaning process
- Data model and star schema diagram
- All 17 DAX measures with exact formulas
- Dashboard visual explanations
- Key findings and business insights
- Problems identified with evidence
- Solutions and recommendations
- Value creation analysis
- GitHub upload guide

### Presentation (12 slides)
- Slide 1: Title and headline KPIs
- Slide 2: Business questions answered
- Slide 3: Raw data and problems found
- Slide 4: Data cleaning steps
- Slide 5: Data model star schema
- Slide 6: Executive KPI summary
- Slide 7: What drives sales
- Slide 8: Who are our customers
- Slide 9: Where are the delays
- Slide 10: Sales performance trends
- Slide 11: Problems matched with solutions
- Slide 12: Value created by this dashboard
```

5. Commit message:
```
Add Documentation folder with README explaining all docs
```
6. Click **"Commit new file"** ✅

---

### Create a "Dashboard" Folder

1. Click **"Add file"**
2. Click **"Create new file"**
3. Type:
```
Dashboard/README.md
# 📊 Dashboard Folder

This folder contains the main Power BI dashboard file.

## Files

| File | Description |
|------|-------------|
| `Sales.pbix` | Complete interactive Power BI dashboard |
| `Dashboard.png` | Screenshot preview of the dashboard |

## How to Open the Dashboard

### Requirements
- Microsoft Power BI Desktop (free download)
- Windows 10 or later
- Minimum 4GB RAM recommended

### Steps
1. Download Power BI Desktop from [microsoft.com/powerbi](https://powerbi.microsoft.com/downloads/)
2. Download `Sales.pbix` from this repository
3. Double-click the .pbix file to open
4. The dashboard loads with all data connected

## Dashboard Features

### Interactive Year Buttons
- Click [2010] [2011] [2012] [2013] [2014] buttons
- Every visual updates instantly to that year
- Click again to deselect and see all years

### Cross-Filtering
- Click any bar, slice, or data point
- All other visuals filter automatically
- Click blank area to reset all filters

## Dashboard Pages

| Page | Content |
|------|---------|
| Page 1 | Sales Performance Overview — KPIs, revenue trends, regional analysis |
| Page 2 | Product Analysis — Top vs bottom products, category breakdown |
| Page 3 | Customer Insights — Demographics, occupation, education, income |
| Page 4 | Shipping and Operations — Delivery performance, order volume |

## Key Metrics Visible

| Metric | Value |
|--------|-------|
| Total Revenue | $29.4 Million |
| Profit Margin | 41.1% |
| Total Orders | 60,399 |
| Unique Customers | 18,484 |
| On-Time Delivery | 100% |
| Avg Ship Days | 7 Days |
```


