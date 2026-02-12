Global Sales Intelligence Dashboard

<img width="1164" height="651" alt="image" src="https://github.com/user-attachments/assets/b86e8be0-9b8a-42c7-aca2-e9926dc62d55" />

🎯 Project Goal
The goal of this project was to transform raw sales data into a dynamic, interactive Business Intelligence solution. Unlike simple flat-file reports, this dashboard is built on a robust Data Model to ensure scalability and performance.

It enables Sales Managers and Executives to:

Track Growth: Monitor Year-Over-Year (YoY) revenue and order volume.

Analyze Trends: Identify seasonal patterns and top-performing markets.

Deep Dive: Drill down into specific Product Variants and Customer Segments.

💻 Technologies & Tools
Microsoft Power BI – Dashboarding and interactivity.

Star Schema Modeling – Designed a professional data model with Fact and Dimension tables for optimal performance.

DAX (Data Analysis Expressions) – Used for Time Intelligence calculations (YoY %, YTD) and dynamic measures.

Power Query (ETL) – Data cleaning, type conversion, and creating conditional columns.

SQL Logic – The data structure reflects standard Data Warehouse principles (Fact/Dim).

🏗️ Data Architecture 

<img width="998" height="637" alt="image" src="https://github.com/user-attachments/assets/7731fe9c-ee0b-4d35-9189-5021e4d334fc" />


1. Star Schema Design
The Foundation: Instead of using a single flat table, I designed a Star Schema centered around the fact_sales_monthly table.

Dimensions: Connected to dim_product, dim_customer, and dim_date via one-to-many relationships.

Why it matters: This structure drastically improves report performance and allows for accurate slicing and dicing of data across multiple viewpoints (Market, Product, Time).

📊 Key Modules & Insights
1. Yearly Overview & Time Intelligence
The Insight: Implemented Time Intelligence measures to calculate Revenue YoY% growth (+324.22%).

Business Value: Provides an instant health check of the business, highlighting massive growth periods and seasonal peaks (e.g., end-of-year spikes).

2. Market & Customer Segmentation
The Insight: A breakdown of Revenue by Channel (Retailer vs. Direct) and Platform (Brick & Mortar vs. E-Commerce).

Business Value: Identifies that while E-Commerce is growing, traditional Retailers still contribute significantly to the core revenue stream.

3. Product Performance
The Insight: Detailed analysis of sales by Product Variant (Plus, Premium, Standard).

Business Value: Helps inventory managers understand which product versions drive the most volume in specific markets (e.g., India vs. USA).

📂 Project Structure
The repository is organized as follows:

images/ - Folder containing screenshots (data_model.png, yearly_overview.png, etc.).

Sales_Analysis.pbix - The main Power BI file containing the data model and report.

README.md - Documentation (This file).

🚀 How to Run
Download the Sales_Analysis.pbix file.

Open in Power BI Desktop.

Navigate to the "Model View" tab to inspect the Star Schema relationships and the _Measures table.

👤 Author
Piotr Pszenny
Aspiring Risk & Data Analyst | Gdańsk Tech
