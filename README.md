# Customer_shopping_behavior_Analysis.
Data analytics project on Customer shopping behavior analysis using python, Postgresql and Power Bi.

🛍️ Customer Shopping Behavior Analysis

📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The objective is to uncover spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

The project demonstrates an end-to-end data analytics workflow using Python, SQL (PostgreSQL), and Power BI, with actionable business recommendations.

Customer Shopping Behavior Anal…

📂 Dataset Summary

Total Records: 3,900

Total Columns: 18

Data Type: Structured transactional data

Key Features

Customer Demographics:
Age, Gender, Location, Subscription Status

Purchase Details:
Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior:
Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

Data Quality

Missing Values:
37 missing values in the review_rating column (handled during cleaning)

🛠️ Tools & Technologies

Python – Data loading, EDA, cleaning, and feature engineering
Libraries: pandas, numpy, matplotlib, seaborn

SQL (PostgreSQL) – Business-focused analytical queries

Power BI – Interactive dashboard development

Jupyter Notebook – Analysis and documentation

🔍 Data Preparation & EDA (Python)

Loaded dataset using pandas

Reviewed structure and summary statistics (df.info(), df.describe())

Handled missing values by imputing review ratings using category-wise medians

Standardized column names to snake_case

Performed feature engineering:

Created age_group for demographic analysis

Derived purchase frequency features

Identified redundancy between discount_applied and promo_code_used and removed unnecessary columns

Loaded cleaned dataset into PostgreSQL for SQL analysis

🧮 SQL Analysis (PostgreSQL)

Performed structured SQL queries to answer key business questions, including:

Revenue comparison by gender

Identification of high-spending discount users

Top 5 products by average review rating

Purchase amount comparison by shipping type

Subscribers vs. non-subscribers revenue analysis

Products most dependent on discounts

Customer segmentation (New, Returning, Loyal)

Top 3 products within each category

Relationship between repeat purchases and subscriptions

Revenue contribution by age group

📊 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize insights, including:

Key revenue KPIs

Customer segment distribution

Product performance and ratings

Subscription and discount impact

Demographic-based revenue trends

📈 Key Insights & Business Recommendations

Boost Subscriptions: Offer exclusive benefits to increase subscriber conversion

Strengthen Loyalty Programs: Incentivize repeat customers to move into loyal segments

Optimize Discount Strategy: Balance promotional impact with profit margins

Improve Product Positioning: Promote top-rated and best-selling products

Targeted Marketing: Focus campaigns on high-revenue age groups and express-shipping customers

▶️ How to Run the Project

Clone the repository

git clone <repository-url>


Install required Python libraries

pip install -r requirements.txt


Run the Jupyter Notebook for data analysis

jupyter notebook


Execute SQL scripts on PostgreSQL

Open the Power BI .pbix file to explore the dashboard

📁 Project Structure
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── customer_shopping_analysis.ipynb
├── sql/
│   └── business_queries.sql
├── powerbi/
│   └── customer_dashboard.pbix
├── reports/
│   └── project_report.pdf
├── requirements.txt
└── README.md

🎯 Skills Demonstrated

Exploratory Data Analysis (EDA)

Data Cleaning & Feature Engineering

SQL Business Analytics

Dashboarding & Data Visualization

Business Insight Generation

End-to-End Analytics Project Delivery
