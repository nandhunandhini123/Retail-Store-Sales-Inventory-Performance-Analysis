# Retail-Store-Sales-Inventory-Performance-Analysis
📌 Project Overview

This project focuses on analyzing retail store sales and inventory performance using Python and Power BI.

The dataset contains 73,100 records and 15 original columns, covering sales, products, inventory, pricing, discounts, and demand forecasts from 2022 to 2024.

The main goal is to identify sales trends, understand revenue performance, and analyze inventory levels to support better business decisions.

🎯 Project Objectives

Analyze retail sales and revenue performance.

Identify top-performing product categories and regions.

Understand the impact of discounts, promotions, and seasonality.

Identify overstock and low-stock situations.

Analyze demand forecasts and inventory performance.

Generate business insights to support inventory planning.

📂 Dataset Information

Domain: Retail / E-commerce

Records: 73,100

Original Columns: 15

Time Period: 2022–2024

Data Source: Kaggle – Retail Store Inventory Forecasting Dataset

Original Dataset Columns

Date, Store ID, Product ID, Category, Region, Inventory Level, Units Sold, Units Ordered, Demand Forecast, Price, Discount, Weather Condition, Holiday/Promotion, Competitor Pricing, Seasonality.

🛠️ Tools & Technologies

Tool / Library

Purpose

Python

Data analysis and calculations

Google Colab

Python coding environment

Pandas

Data cleaning and manipulation

NumPy

Numerical calculations

Matplotlib

Data visualization

Seaborn

Statistical visualizations

Power BI

Interactive dashboard creation

🔄 Project Workflow

1. Data Loading & Inspection

Imported the dataset using Pandas.

Checked dataset structure, dimensions, and data types.

Reviewed statistical summaries.

2. Data Cleaning & Pre-processing

Checked for missing values and duplicate records.

Converted the Date column into datetime format.

Extracted Year and Month from the Date column.

Created additional calculated columns for analysis.

3. Feature Engineering

The following additional columns were created:

Year: Extracted year from the Date column.

Month: Extracted month from the Date column.

Revenue: Sales revenue before discounts.

Net Revenue: Revenue after discounts.

Stock Status: Classified inventory into Normal, Overstock, and Low Stock.

Demand Difference: Difference between demand forecast and units sold.

Estimated Remaining Stock: Estimated stock remaining after sales.

Price Difference: Difference between product price and competitor pricing.

4. Exploratory Data Analysis (EDA)

Performed analysis using different visualizations:

Category-wise Revenue – Bar Chart

Stock Status Distribution – Count Plot

Units Sold Distribution – Histogram

Seasonality-wise Net Revenue – Box Plot

Demand Forecast vs Units Sold – Scatter Plot

Correlation Analysis – Heatmap

Sales and Inventory Relationship – Pair Plot

Revenue by Category and Region – Heatmap

Year-wise Category Revenue Trend – Line Chart

Stock Status vs Inventory Level – Violin Plot

5. Power BI Dashboard

Created an interactive dashboard to present key business insights.

Dashboard Highlights:

Total Net Revenue

Average Revenue

Total Units Sold

Category-wise Revenue

Region-wise Sales

Monthly Revenue

Stock Status Distribution

Weather and Demand Analysis

📊 Key Insights

Furniture was identified as a high-performing category in terms of revenue.

Inventory analysis helped identify overstock and low-stock situations.

Demand Forecast and Units Sold showed a positive relationship.

Revenue performance varied across product categories and regions.

Seasonal and promotional factors provided additional insights into retail performance.

💡 Business Recommendations

Maintain optimal inventory levels to reduce overstock and stock shortages.

Use demand forecasts to support inventory replenishment decisions.

Monitor category-wise and region-wise sales performance.

Plan suitable discounts and promotions to improve sales.

Review seasonal demand patterns for better inventory planning.

🏁 Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, feature engineering, and data visualization using Python. The Power BI dashboard presents key sales and inventory insights in an interactive format. These findings can help businesses improve inventory planning and make data-driven decisions.

🚀 Future Enhancements

Use larger and more recent datasets for deeper analysis.

Implement Machine Learning models for demand forecasting.

Automate inventory tracking and stock monitoring.

Develop more interactive dashboards with additional insights.

Improve inventory planning using predictive analytics.

👩‍💻 Author

Nandhini S

Aspiring Data Analyst

Skills: Python | SQL | Excel | Power BI | Data Analysis


