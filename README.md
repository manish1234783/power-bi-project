# Sales & Profitability Analytics Dashboard

Short Description
An interactive business intelligence solutions platform designed to track, analyze, and visualize core retail performance metrics. The project converts raw transactional data into actionable insights, enabling stakeholders to monitor financial health, optimize regional strategies, and evaluate customer demographic behaviors


#  Tech Stack
Business Intelligence: Microsoft Power BI (DAX, Power Query)

Database Management: SQL / Microsoft SQL Server

Data Modeling: Star Schema / Snowflake Schema methodologies


#Data Source
Dataset: Retail sales, inventory, and customer transactions structured similarly to the AdventureWorks dataset
Source:Excelr


# Features and Highlights
Dynamic Financial Tracking: Built robust DAX measures to calculate real-time revenue growth, gross profit margins, and year-over-year (YoY) performance shifts.

Regional Customer Analytics: Designed geospatial maps and regional matrices to isolate top-performing territories and identify customer purchasing trends across different zones.

Interactive Filtering & Slicers: Implemented advanced filtering options (by date, product category, and region) to allow users to seamlessly drill down into granular transactional details.

Optimized Data Model: Structured an efficient star schema model to handle complex data relationships and ensure high-performance report responsiveness

# Key Queastions Such as

Use the Attached Sales Excel sheet and perform the following actions:
I . Append/Union of Fact Internet sales and Fact internet sales new - SALES
II. Merge Products, ProductCategory and ProductSubCategory Tables
0. Create Relationships between Tables
1. Lookup the Productname from the Product sheet to Sales sheet.
2. Lookup the Customerfullname from the Customer Table and Unit Price from Product Table to Sales sheet.
3. Calcuate the following fields from the Orderdatekey field (First Create a Date Field from Orderdatekey)
   A. Year
   B. Monthno
   C. Monthfullname
   D. Quarter(Q1,Q2,Q3,Q4)
   E. YearMonth ( YYYY-MMM)
   F. Weekday Number
   G. Weekday Name
   H. Financial Month (** Financial Year starts from April and ends at March - April : 1, May : 2 ….. March : 12)
   I. Financial Quarter 
4. Calculate the Sales amount using the columns (Unit price, Order quantity, Unit discount)
5. Calculate the Productioncost using the columns (Unit cost, Order quantity)
6. Calculate the Profit. (Sales - ProductionCost)
7. Create a Pivot table for month and sales (provide the Year as filter to select a particular Year)
8. Create a Bar chart to show Yearwise Sales
9. Create a Line Chart to show Monthwise sales
10. Create a Pie chart to show Quarterwise sales
11. Create a Combo chart (bar and Line) to show Salesamount and Productioncost together
12. Build addtional KPI/Charts for Performance by Products, Customers, Region
13. Create one or more Dashboards based on the requirement

# ScreenShorts / Demo



