SQL Data Analytics Project – Sales Analysis
📌 Project Overview

This project focuses on analyzing sales data using Microsoft SQL Server (MS SQL) to uncover meaningful business insights and identify key trends in customer behavior, product performance, and overall sales performance.

The project follows a structured data analytics workflow, starting with Exploratory Data Analysis (EDA) on clean datasets and progressing toward advanced analytical techniques. The final stage involves creating SQL views to consolidate the analysis into comprehensive Customer Reports and Product Reports.

The main objective is to transform raw sales data into meaningful insights that can support data-driven business decisions.

🗂️ Data Model

The project consists of three main tables:

Table	Description	Type
fact_sales	Contains detailed sales transaction records.	Fact Table
dim_customers	Contains customer-related information.	Dimension Table
dim_products	Contains product-related information.	Dimension Table

The data model follows a Star Schema approach, where the fact table is connected to customer and product dimension tables.

🔍 1. Exploratory Data Analysis (EDA)

The first stage of the project focuses on understanding the structure, characteristics, and overall distribution of the datasets.

The following analyses were performed:

Dimension Exploration: Examined the structure and attributes of dimension tables to understand customer and product information.
Date Exploration: Identified the date range of the sales data and examined the available time period.
Overall Measures: Calculated key business metrics to understand the overall performance of the dataset.
Magnitude Analysis: Analyzed the magnitude of sales-related measures across different business dimensions.
Top-N Ranking Analysis: Identified top-performing customers and products based on sales metrics.
📊 2. Advanced Data Analysis

After completing the initial EDA, advanced analytical techniques were applied to discover deeper business insights.

2.1 Change Over Time Analysis

Analyzed how key business metrics evolved over time to identify trends, patterns, and changes in sales performance.

2.2 Cumulative Analysis

Calculated running totals and cumulative measures to evaluate the progression of sales over time.

2.3 Performance Analysis

Evaluated business performance by comparing current results with previous periods and identifying performance improvements or declines.

2.4 Part-to-Whole Analysis

Examined the contribution of individual customers and products to total sales to understand their relative importance.

2.5 Data Segmentation

Segmented customers and products based on their characteristics and performance to identify meaningful groups and behavioral patterns.

📑 3. Reporting and SQL Views

In the final stage, the analytical results were consolidated using SQL Views.

Two comprehensive reports were created:

Customer Report

Customer-level sales performance.
Customer contribution to total sales.
Customer purchasing behavior.
Customer segmentation and related metrics.

Product Report

Product-level sales performance.
Product contribution to total revenue.
Product performance comparisons.
Product segmentation and related metrics.

These views provide a structured and reusable reporting layer, making the analytical results easier to access and interpret.

🛠️ Tools & Technologies
Microsoft SQL Server (MS SQL): Database management and data analysis.
SQL: Data exploration, aggregation, analytical calculations, and reporting.
SQL Views: Consolidation of analytical results into reusable reporting structures.
🎯 Key Skills Demonstrated

Through this project, the following data analytics skills were demonstrated:

Relational database exploration.
Fact and dimension table analysis.
Exploratory Data Analysis (EDA).
Business metrics calculation.
Magnitude and ranking analysis.
Time-based trend analysis.
Cumulative calculations.
Performance analysis.
Part-to-whole analysis.
Customer and product segmentation.
SQL-based reporting and data modeling.


🚀 Conclusion

This project demonstrates an end-to-end SQL data analytics workflow, from understanding and exploring sales data to performing advanced business analysis and building consolidated reporting views.

By applying various SQL analytical techniques, the project transforms transactional sales data into actionable business insights, providing a foundation for better understanding customer behavior, product performance, and overall sales trends.
