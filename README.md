Customer Shopping Behavior Analysis

This project analyzes customer shopping patterns using SQL, Python EDA, and Power BI. It provides insights into spending behavior, discounts, product performance, shipping preferences, and subscription impact.

Dataset Description

The dataset contains:

Customer demographics (age, gender, location)

Product details (item purchased, category, size, color, season)

Shopping behavior (purchase amount, discount applied, promo code used)

Customer value indicators (previous purchases, subscription status)

Experience metrics (review rating, shipping type)

Payment method and purchase frequency

Technologies Used

SQL (MySQL)

Python (Pandas, Matplotlib, Seaborn)

Power BI

Jupyter Notebook

SQL Analysis Overview

Total revenue by gender

Customers who used a discount but spent above average

Top 5 products with highest average review rating

Average spend comparison: Standard vs Express shipping

Revenue and spending comparison between subscribers and non-subscribers

Products with highest discount usage rate

Python EDA Highlights

Data cleaning and preprocessing

Handling missing values

Distribution analysis (age, purchase amount, ratings)

Category-wise sales patterns

Correlation heatmap

Outlier detection

Power BI Dashboard Features

Revenue summary

Gender-based spending trends

Product performance visualization

Subscription impact analysis

Discount and promo code usage

Shipping method insights

How to Run

SQL:

create database customer_shopping;
use customer_shopping;
source project_eda_sql_powerbi.sql;


Python:

import pandas as pd
df = pd.read_csv('customer_shopping_behavior.csv')


Power BI:
Open the .pbix file to view the interactive dashboard.

Project Structure
customer_shopping_behavior.csv
project_eda_sql_powerbi.sql
customer_behavior_dashboard.pbix
Untitled.ipynb
README.md

Image:
<img width="1127" height="617" alt="image" src="https://github.com/user-attachments/assets/049f6435-6930-4da4-b9ea-e6c8bb54d663" />


