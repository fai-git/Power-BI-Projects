Sales & Customer Insights Dashboard — Power BI Project

1. Project Overview
This project analyzes sales and customer behavior using the Superstore dataset. A fully interactive Power BI dashboard is created to explore KPIs, regional performance, customer segments, discounts, and profit distribution. The goal is to help businesses identify:
a. Top-performing categories
b. Most profitable segments
c. Regional sales trends
d. Discount impacts
e. Shipping preferences

2. Dataset Used
Source: Kaggle — Superstore Sales Dataset
Dataset Link: https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset
Rows: ~10,000
Columns: Order details, customer info, shipment mode, sales, profit, category, geography, etc.

3. Project Workflow

Data Cleaning:
Checked missing values
Standardized date formats
Corrected data types (e.g., Order Date → Date)
Added calculated fields
Removed duplicates
Data Modeling
Star schema layout
Created relationships among Orders, Customers, Products, and Regions
DAX Measures
Created important measures:
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
Avg Discount = AVERAGE(Orders[Discount])
Report Building
Created multiple visuals including:
KPI Cards
Bar Charts
Donut Charts
Maps (Sales by State)
Slicers for interactive filtering 

6. Key Features
KPI Cards → Total Sales, Profit, Margin %, Discount
Sales Performance → Category-wise & Sub-category profitability
Customer Insights → Segment distribution & average discount
Geographic Analysis → State-wise sales map
Filters → Region, Segment, Ship Mode, Category

7. Insights Discovered

Technology category brings the highest revenue
West region performs best in overall sales
Home Office segment shows stable profitability
Standard shipping mode is most used
Higher discounts lead to lower profit margins



8. Tools Used
Power BI
Power Query
DAX
Microsoft Excel
Data Visualization Techniques

