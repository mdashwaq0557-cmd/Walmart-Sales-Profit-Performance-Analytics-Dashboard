# Walmart-Sales-Profit-Performance-Analytics-Dashboard
📊 Power BI Business Intelligence Dashboard

An interactive Power BI dashboard developed to analyze Walmart sales and profitability performance across products, categories, customers, locations, orders, and shipping operations.

The project transforms raw Walmart sales transaction data into an interactive business intelligence solution using Power Query, DAX, data modeling, and Power BI visualizations.

📌 Project Overview

The Walmart Sales & Profit Performance Analytics project is a one-page Power BI dashboard designed to provide a consolidated view of business performance.

The dashboard enables users to analyze:

Total Sales
Total Profit
Profit Margin
Total Orders
Total Quantity
Total Customers
Total Products
Sales & Profit Trends
Category Performance
Product Performance
Geographic Performance
Monthly Order Trends
Shipping Performance
Dynamic Business Insights

Interactive slicers allow users to filter the dashboard by Year, Month, Category, City, and State.

🎯 Project Objectives

The primary objectives of this project are:

Analyze overall sales performance.
Evaluate profitability and profit margins.
Identify high-performing product categories.
Identify top-selling products.
Analyze sales performance across states and cities.
Understand customer contribution to sales.
Analyze monthly sales and order trends.
Evaluate shipping performance.
Build dynamic KPIs using DAX.
Create interactive business insights.
Present the analysis through a professional one-page Power BI dashboard.
📂 Dataset

The project uses a Walmart sales transaction dataset stored in Excel format.

Dataset File
walmart.xlsx
Dataset Size

The dataset contains:

Metric	Value
Records	3,203
Unique Orders	1,611
Customers	686
Products	1,494
Categories	17
States	11
Cities	169
Country	United States
Total Sales	$725,457.82
Total Profit	$108,418.45
Total Quantity	12,264
Profit Margin	14.94%
Average Order Value	$450.32
Order Date Range	2011–2014
Shipping Days	0–7 days

The metrics above were calculated directly from the dataset used for this project.

🗂️ Dataset Columns

The original dataset contains the following 12 columns:

Column	Description
Order ID	Unique order identifier
Order Date	Date when the order was placed
Ship Date	Date when the order was shipped
Customer Name	Name of the customer
Country	Country associated with the transaction
City	City associated with the transaction
State	State associated with the transaction
Category	Product category
Product Name	Name of the product
Sales	Sales/revenue generated
Quantity	Number of units sold
Profit	Profit generated from the transaction

A calculated Shipping Days field was also created during data preparation.

🛠️ Tools & Technologies
Microsoft Power BI

Used for:

Dashboard development
Data visualization
KPI cards
Interactive filtering
Business intelligence analysis
Power Query

Used for:

Data cleaning
Data transformation
Data type correction
Creating the Shipping Days column
DAX

Used for:

KPI calculations
Profitability analysis
Time intelligence
Year-over-year analysis
Dynamic business insights
Top-performing category/product analysis
Microsoft Excel

Used as the source data format.

🔄 Data Preparation

The following data preparation process was performed in Power BI Power Query:

Imported the walmart.xlsx dataset.
Loaded the Walmart worksheet.
Renamed the table/query to Walmart_Sales.
Verified all column names.
Corrected column data types.
Converted Order Date to Date.
Converted Ship Date to Date.
Converted Sales and Profit to Decimal Number.
Converted Quantity to Whole Number.
Checked the dataset for missing/invalid values.
Created a calculated Shipping Days column.
Loaded the transformed data into Power BI.
Created a dedicated Date Table.
Created a relationship between the Date Table and the sales table.
