# Cafe-Sales-Data-Analysis 📊
## 🎯 Project Overview
This project presents a comprehensive analysis of cafe sales data from 2023, demonstrating end-to-end data science workflow from dirty data cleaning to business insights visualization. The analysis reveals critical business patterns, identifies revenue optimization opportunities, and provides actionable recommendations for cafe operations.
#### Dataset Source: Kaggle - [Kaggle - Cafe Sales Dirty Data](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training/data?select=dirty_cafe_sales.csv)

## 🗂️ Project Structure
```
cafe-sales-analysis/
│
├── data/
│   └── dirty_cafe_sales.csv          # Raw dataset from Kaggle
│
├── notebooks/
│   └── Cafe-Data.ipynb               # Data cleaning and analysis
│
├── dashboard/
│   └── Cafe-Sales-Dashboard.jpeg     # Tableau visualization
│
├── docs/
│   └── analysis-report.md            # Detailed findings
│
└── README.md                         # This file
```
## 🧹 Data Cleaning Process
### 1. Python Analysis
#### Original Data Quality Issues
The raw dataset presented several quality challenges that required careful cleaning to ensure reliable analysis.
* The dataset initially contained several gaps, with missing product names, quantities, unit prices, payment methods, locations, and even transaction dates, limiting reliable analysis.
* Alongside this, inconsistencies such as UNKNOWN categories, ERROR values in financial fields, and mixed formatting further reduced data quality.
* To resolve these issues, the data was systematically cleaned by converting columns to proper types, standardizing categories, and creating derived metrics that enabled deeper business insights.
### 2. Dashboard Analysis
The Tableau dashboard was designed to transform cleaned sales data into clear business insights, focusing on overall performance, customer behavior, and operational trends.
* The dashboard highlights overall performance with key cards showing total sales, orders, units sold, and averages for both order size and order value.
* It breaks down revenue by product category, provides performance rankings, and shows contribution percentages to identify best-selling items. Customer preferences are revealed through the distribution of payment methods along with insights into performance.
* Monthly sales patterns and seasonal fluctuations are visualized to uncover growth opportunities and peak periods.

## 🔍 Key Findings






