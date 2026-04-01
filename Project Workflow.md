Project Workflow – Customer Churn Analysis

This document outlines the complete workflow followed to build the customer churn analysis project.

1. Data Collection
Imported raw CSV / Excel files containing:
Customers
Churn
Subscriptions
Transactions
2. Initial Data Validation
Checked schema and column names
Identified date format inconsistencies
Found hidden BOM character in CustomerID column
Validated null values and data types
3. Data Cleaning
Renamed corrupted column names
Converted date columns to SQL DATE format
Standardized formats across all tables
Validated joins and primary keys
4. SQL Analysis

Performed business KPI analysis in MySQL:

total customers
active vs inactive customers
churn rate
churn reasons
revenue by region
ARPU
subscription duration
top customers
5. Dashboard Development (Power BI)

Loaded cleaned dataset into Power BI in import mode.

Created dashboard pages for:

Overview
Churn Analysis
Revenue Insights
Subscription Metrics

Used:

KPI cards
bar charts
line charts
donut charts
slicers
DAX measures
6. Business Insights

Generated key insights on:

churn trends
customer retention
revenue growth
regional performance
subscription behavior
7. Final Delivery

Published final project with:

SQL file
PBIX dashboard
dashboard screenshots
README documentation
