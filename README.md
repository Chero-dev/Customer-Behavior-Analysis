Customer Shopping Behavior Analysis
Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

 Dataset Summary
Rows: 3,900
Columns: 18

Key Features:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
Shopping behavior (Discount Applied, Promo Code Used, Review Rating, Frequency of Purchases, Shipping Type)
Missing Data: 37 values in Review Rating column

Data Preparation and Cleaning (Python)
Imported dataset using pandas and performed exploratory data analysis.
Handled missing values in Review Rating by imputing median values per product category.
Renamed columns to snake_case for consistency.
Engineered new features such as age_group and purchase_frequency_days.
Loaded the cleaned dataset into PostgreSQL for structured SQL analysis.

 Data Analysis (SQL – MSSQL)
Conducted SQL queries to answer key business questions, including:
Revenue by gender and age group.
Comparison of spending between subscribers and non-subscribers.
Identification of high-spending discount users.
Top 5 products by rating and category.
Shipping type performance (Standard vs Express).
Customer segmentation (New, Returning, Loyal).

Visualization (Power BI)
Developed an interactive Power BI dashboard showcasing:
Revenue breakdowns by demographic and subscription status.
Customer segments and purchase frequency.
Product category performance and top-rated items.
building interactive dashboards in Power BI.

