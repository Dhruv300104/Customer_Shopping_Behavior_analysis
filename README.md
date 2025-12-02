This repository contains a complete data analysis project that examines customer shopping behavior using Python, SQL, and Power BI. The project demonstrates the full workflow of data cleaning, exploratory data analysis (EDA), SQL-based insight generation, and dashboard creation.

Project Overview

The objective of this project is to understand customer purchasing patterns and identify insights that can help businesses optimize decision-making.
The analysis focuses on customer demographics, spending behavior, purchase frequency, and product category performance.

The project includes:

Python-based data cleaning and exploratory analysis
SQL queries for advanced analytical insights
A Power BI dashboard for interactive visualization

Repository Structure

Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.ipynb      # Python notebook for EDA and preprocessing
├── customer_behavior_sql_queries.sql      # SQL queries used for analysis
├── customer_behavior_dashboard.pbix       # Power BI dashboard file
├── README.md                              # Project documentation
└── data/                                  # Optional dataset folder

1. Data Cleaning and Exploratory Analysis (Python)

File: customer_shopping_behavior.ipynb

This section includes:

Loading and understanding the dataset
Handling missing values and correcting data types
Detecting and treating outliers
Creating new features such as age groups and revenue metrics
Performing exploratory data analysis using visualizations and descriptive statistics

Technologies: pandas, NumPy, matplotlib, seaborn

To run the notebook:

Install required libraries:

pip install pandas numpy matplotlib seaborn jupyter


Start Jupyter Notebook:

jupyter notebook


Open and execute the file.

2. SQL-Based Insights

File: customer_behavior_sql_queries.sql

This section contains SQL queries that generate insights such as:

Customer segmentation
Top-spending customers
Category-level performance
Monthly and yearly sales trends
Behavioral patterns across gender, age groups, and location
CTEs, JOINs, and window function-based analysis

Queries can be executed in any SQL database system, such as MySQL, PostgreSQL, SQL Server, or SQLite.

3. Power BI Dashboard

File: customer_behavior_dashboard.pbix

The Power BI dashboard provides:

Key performance indicators (KPIs)
Customer segmentation views
Revenue trends over time
Product category performance
Filters for demographic and category-based exploration

To run the dashboard:

Install Power BI Desktop
Open the .pbix file
Interact using slicers and filters

- Tools and Technologies

Python (pandas, NumPy, matplotlib, seaborn)
SQL
Power BI
Jupyter Notebook

- Key Outcomes

A clean and well-structured dataset ready for analysis
Insightful SQL queries highlighting customer behavior patterns
A visually clear and interactive Power BI dashboard
A complete end-to-end data analytics workflow demonstrating practical business intelligence skills

- Usage

This project can be used as:

A portfolio project for data analytics roles
A reference for learning data cleaning, EDA, SQL analytics, and dashboard creation
A template for building similar business intelligence projects
