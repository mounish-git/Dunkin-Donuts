# Dunkin-Donuts
Project Overview
This project focuses on designing and implementing a Data Warehouse (DW) and Business Intelligence (BI) system for Dunkin’ Donuts, a global leader in the quick-service restaurant industry. The goal is to create a centralized data repository that enables data-driven decision-making across different business operations, including sales, inventory, customer behavior, and financial performance.

By leveraging ETL (Extract, Transform, Load) processes, dimensional modeling, and OLAP (Online Analytical Processing) cubes, this system enhances data accessibility, improves forecasting accuracy, and optimizes resource allocation.

Project Objectives
Centralized Data Repository: Establish a data warehouse to consolidate data from multiple sources (e.g., sales transactions, customer interactions, and inventory management).
Robust Data Architecture: Ensure data integrity, security, and scalability through well-defined ETL pipelines.
Business Intelligence & Reporting: Develop dashboards and self-service BI tools for executives and managers.
Data-Driven Decision Making: Enable data analysis for sales trends, customer behavior, inventory optimization, and operational efficiency.
Technologies Used
Data Extraction & ETL: SQL, Python
Data Storage: PostgreSQL, Snowflake
Data Modeling: Star Schema, OLAP Cubes
Business Intelligence: Tableau, Power BI
Project Management: Jira, Confluence
Data Sources
The project integrates data from various sources, including:

Point of Sale (POS) Systems: Tracks customer purchases across store locations.
Inventory Management: Monitors stock levels and restocking patterns.
Customer Transactions: Includes mobile orders, loyalty programs, and promotional activities.
Financial Reports: Provides insights into revenue trends and cost optimization.
Data Warehouse Architecture
1. Data Extraction & Transformation (ETL)
Extract data from multiple sources (Excel, API, SQL databases).
Transform data by cleaning, normalizing, and handling missing values.
Load structured data into the warehouse.
2. Dimensional Modeling
Implemented a Star Schema to optimize query performance.
Designed Fact Tables (e.g., Walk-In Orders, Mobile Orders) and Dimension Tables (e.g., Store, Product, Date).
3. OLAP Cube Development
Built Multidimensional Data Cubes (MDDB) to analyze trends in Order Type, Product Type, and Payment Method.
Enabled drill-down analysis for sales forecasting and customer segmentation.
Key Features
1. Business Intelligence Dashboards
Developed interactive BI dashboards for sales, inventory, and customer behavior analysis:

Sales Performance: Compare revenue across locations and time periods.
Inventory Optimization: Identify fast-moving and slow-moving items.
Customer Insights: Analyze purchase patterns and targeted marketing opportunities.
2. Data Transformation & Cleaning
Applied data validation rules to ensure quality.
Unified coding structure across multiple data sources.
Merged duplicate columns and removed redundancies for consistency.
3. Performance Optimization
Reordered queries to improve efficiency.
Used indexing and partitioning for faster lookups.
Implemented Slowly Changing Dimensions (SCDs) to track historical data changes.
