#Sales Data Analysis | Excel & Power BI
Project Overview
An end-to-end sales analytics portfolio project using a synthetic retail sales dataset. The project demonstrates data preparation, KPI analysis, trend analysis, and dashboard design using Microsoft Excel and Power BI.
Business Questions
How much revenue and profit did the business generate?
Which product categories and products perform best?
Which regions contribute the most sales?
How do sales change month over month?
Which customer segments and sales channels contribute most?
What are the average order value and profit margin?
Tools
Microsoft Excel: data review, summary analysis, charts and PivotTable-ready data
Microsoft Power BI: interactive dashboard and DAX measures
Git & GitHub: version control and portfolio presentation
Dataset
File: `sales_data.csv`
Rows: 1,200 orders
Period: 2024-01-02 to 2025-12-30
Fields: Order ID, Order Date, Customer Segment, Region, City, Sales Channel, Category, Product, Quantity, Unit Price, Discount, Sales, Cost, Profit.
Important: This is synthetic sample data created for learning and portfolio demonstration. It does not represent a real company.
Repository Structure
```text
sales-data-analysis/
├── data/
│   └── sales_data.csv
├── excel/
│   └── Sales_Analysis.xlsx
├── powerbi/
│   ├── DAX_Measures.txt
│   └── dashboard_screenshot.png   # Add your Power BI screenshot here
└── README.md
```
Excel Analysis
Open `Sales_Analysis.xlsx`. It contains:
Raw Data: source transactions, filters and frozen headers
Monthly Analysis: monthly sales, profit, orders and units sold
Category Analysis: sales and profit by category
Region Analysis: sales and profit by region
Power BI Dashboard — Build Steps
Open Power BI Desktop.
Select Get Data → Text/CSV and import `sales_data.csv`.
Confirm `Order Date` is Date, `Discount` is Percentage, and `Sales`, `Cost`, `Profit` are Decimal Number / Fixed Decimal Number.
Rename the table to `Sales`.
Add a Date table and measures from `DAX_Measures.txt`.
Mark the Date table as the date table and relate `Date[Date]` to `Sales[Order Date]`.
Build a one-page dashboard with:
KPI cards: Total Sales, Total Profit, Total Orders, Profit Margin
Line chart: Sales by Month
Bar chart: Sales by Category
Bar chart or map: Sales by Region
Donut chart: Sales by Customer Segment
Slicers: Year, Region, Category, Sales Channel
Use a consistent theme, clear titles, and readable number formats.
Save the report as `Sales_Dashboard.pbix`.
Export a dashboard screenshot as `powerbi/dashboard_screenshot.png`.
Suggested Dashboard Layout
Top: title and four KPI cards
Middle: monthly sales trend and category performance
Bottom: regional performance and customer segment mix
Side/top filters: Year, Region, Category, Channel
Key Skills Demonstrated
Data cleaning and validation, Excel analysis, KPI reporting, data visualization, Power Query basics, DAX measures, business insight communication, and GitHub documentation.
How to Run
Download or clone this repository, open the Excel workbook, and import the CSV into Power BI Desktop.
Resume Bullet
Sales Data Analysis | Excel, Power BI
Analyzed 1,200 synthetic sales transactions using Excel and Power BI to evaluate revenue, profitability, product performance, and regional trends.
Developed KPI measures including Total Sales, Total Profit, Average Order Value, and Profit Margin using DAX.
Designed an interactive dashboard with monthly trends, category comparisons, regional analysis, and slicers to support data-driven insights.
