# Customer Behavior Data Analytics Project
# Project Summary

- This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI. The goal is to understand purchasing patterns, identify revenue drivers, analyze product performance, and study how factors like gender, discounts, shipping type, and subscription affect customer spending.
- The project includes data loading, cleaning, EDA, SQL analysis, dashboard creation, and final reporting.

# Project Overview

- Customer shopping platforms generate large amounts of transaction data.
  
# This project aims to:

- Understand how different customer attributes affect purchase amount
- Engineer meaningful features where needed
- Perform exploratory data analysis to identify trends
- Run SQL queries to answer business-related questions
- Build an interactive Power BI dashboard
- Generate insights that help businesses improve decision-making
- Present the results through a clean report and PPT

# Files in This Repository
# File Name	Description
- customer_shopping_behavior.csv	Raw dataset with customer demographic and purchase details
- Customer_behavior.py.ipynb	Python notebook with data loading, cleaning, EDA, and visualizations
- Customer_Behavior_SQL.sql	SQL queries answering 10+ business questions
- Customer_behavior_Dashboard.pbix	Power BI dashboard showing key insights
  
# Tools & Libraries Used
# Python

- Pandas – Data cleaning & preprocessing
- NumPy – Numerical handling
- Matplotlib / Seaborn – Data visualization
- Jupyter Notebook – Analysis environment

# SQL (MySQL)

- Querying data
- Aggregations & grouping
- Window functions
- Subqueries

# Power BI

- Dashboard creation
- Interactive filtering
- KPIs & visual storytelling

# Key Steps Performed
Data Cleaning:

- Removed BOM characters from columns (e.g., fixed ï»¿Customer ID)
- Standardized column names
- Corrected data types for numeric and categorical fields
- Handled missing or inconsistent values
- Validated fields like gender, shipping type, and category

Feature Engineering:

- Created customer segments (New, Returning, Loyal) using previous purchases
- Derived discount usage metrics
- Calculated average rating per product
- Built product- and category-level summaries

Exploratory Data Analysis (EDA):

- Revenue by gender
- Purchase amount distributions
- Top products & categories
- Shipping type comparison (Express vs Standard)
- Subscription vs non-subscription analysis
- Heatmaps & correlations
- Discount usage behavior

# SQL Analysis

Included queries for:

- Total revenue by gender
- Customers using discount but spending above average
- Top 5 highest-rated products
- Average purchase amount by shipping type
- Subscriber vs non-subscriber revenue
- Products with highest discount usage
- Customer segmentation (New/Returning/Loyal)
- Top 3 products per category
- Repeat buyers and subscription tendency
- Age-wise revenue contribution

# Dashboard Building (Power BI)

The dashboard includes:

- Total Revenue
- Revenue by Gender
- Revenue by Age Group
- Top Selling Products
- Average Rating by Product
- Category-wise orders
- Customer Segmentation (New, Returning, Loyal)
- Discount vs Non-discount sales
- Shipping type comparison
- The dashboard enables interactive filtering and drill-down analysis.

# Results & Insights

- Female customers generated slightly higher revenue
- Express shipping users tend to spend more
- Loyal customers (10+ purchases) contribute major revenue
- Some products show strong ratings and high sales
- Discounts attract customers but do NOT always increase spend
- Subscribed customers spend more on average

# How to Use

Download or clone the repository

Open the Python notebook:

Customer_behavior.py.ipynb


Run all cells for data cleaning, EDA, and plots

- Load Customer_Behavior_SQL.sql into MySQL and execute the queries
- Open the Power BI file:
- Customer_behavior_Dashboard.pbix

# Author

Created by: Hema Shrie

📧 Email: rhemashrie156@gmail.com
