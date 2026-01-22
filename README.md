# End-to-End-Shopping-Behavior-Analysis-using-SQL-Python-PowerBI

## 📊 Project Overview

This project performs an end-to-end analysis of customer shopping behavior using transactional retail data containing 3,900 purchase records. The goal is to uncover actionable insights into customer spending patterns, product preferences, subscription behavior, and customer segmentation to support data-driven business decisions.

## 🗂 Dataset Summary

* **Rows:** 3,900
* **Columns:** 18
* **Key Features:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Product, Category, Amount, Season, Size, Color)
  * Shopping behavior (Discounts, Purchase Frequency, Reviews, Shipping Type)
* **Missing Data:** 37 values in the *Review Rating* column (handled during preprocessing)

## 🧹 Data Processing & EDA (Python)

* Data cleaning and preprocessing using **Pandas**
* Handled missing values using category-wise median imputation
* Feature engineering (age groups, purchase frequency)
* Column standardization for consistency
* Loaded cleaned data into **PostgreSQL** for SQL-based analysis

## 🧮 Data Analysis (SQL)

Key business insights derived using SQL queries:

* Revenue comparison by gender and subscription status
* Identification of high-spending discount users
* Top-rated and most-purchased products
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by age group and shipping type

## 📈 Dashboard (Power BI)

An interactive Power BI dashboard was built to visualize:

* Revenue trends
* Customer segments
* Product performance
* Subscription and discount behavior

## 💡 Business Recommendations

* Strengthen subscription programs to improve retention
* Introduce loyalty rewards for repeat customers
* Optimize discount strategies to protect profit margins
* Promote top-rated and best-selling products
* Apply targeted marketing for high-value customer segments

## 🛠 Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib)
* **PostgreSQL (SQL)**
* **Power BI**
* **Jupyter Notebook**
