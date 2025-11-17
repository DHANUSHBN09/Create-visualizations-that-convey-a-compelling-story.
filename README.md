📊 Data Visualization & Storytelling — Superstore Analysis
Deliverables: PDF Visual Report + Power BI/Tableau-Ready Dataset + Storyboard Notes
📌 Project Overview

This project focuses on business data visualization and storytelling using a synthetic Superstore-style dataset.
The goal is to analyze Sales, Profit, Trends, Categories, and Regions, and generate meaningful business insights.

📁 Files Included
File	Description
visual_report.pdf	Final visual analytics report with insights
superstore_synthetic.csv	Full dataset for Power BI/Tableau
storyboard_notes.md	Dashboard planning, KPIs, visuals, recommended layout
PB_Tableau_README.txt	Quick start steps for BI tools
/charts/	Individual PNG charts used in the report
▶️ How to Use (Power BI / Tableau)
1. Import Dataset

Load superstore_synthetic.csv into either Power BI Desktop or Tableau.

2. Create Key Measures (Power BI recommended)

Examples:

Total Sales = SUM(Superstore[Sales])
Total Profit = SUM(Superstore[Profit])
Profit Ratio = DIVIDE([Total Profit], [Total Sales], 0)
Orders Count = DISTINCTCOUNT(Superstore[Order ID])
Average Order Value = AVERAGE(Superstore[Sales])

3. Create a Date Table

(Improves time-series visuals and filtering)

4. Build Visuals (Follow storyboard_notes.md)

Recommended visuals:

Sales by Region (Bar)

Profit Ratio by Region (Bar)

Monthly Sales Trend (Line)

Category & Sub-Category Contribution (TreeMap / Bar)

Profit vs Sales Scatter

KPI Cards: Total Sales, Total Profit, Profit Ratio, Order Count

5. Add Interactivity

Filters: Region, Category, Segment, Date

Drill-down: Category → Sub-Category

Tooltips: Order details

📊 Insights Included in the Report

The generated PDF includes insights such as:

Region-wise sales performance

Profitability trends

Best performing sub-categories

High-sales vs low-profit orders

Seasonal sales patterns

🛠 Tools Used

Python

pandas

matplotlib

PdfPages

📬 How to Reuse or Extend

You can:

Replace the synthetic dataset with your real Superstore dataset

Re-run the visual pipeline

Convert visuals into BI dashboards

Use storyboard notes as a guide for dashboard design



 
