# Cafe-Sales-Data-Analysis 📊
## 🎯 Project Overview
This project presents a comprehensive analysis of cafe sales data from 2023, demonstrating end-to-end data workflow from dirty data cleaning to business insights visualization. The analysis reveals critical business patterns, identifies revenue optimization opportunities, and provides actionable recommendations for cafe operations.
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
└── README.md                         # Project Overview and Findings
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
## Dashboard
![Dashboard](https://github.com/NandanaAnup/Cafe-Sales-Data-Analysis/blob/main/Cafe%20Sales%20Dashboard%20Full.png)
![Dasboard](https://github.com/NandanaAnup/Cafe-Sales-Data-Analysis/blob/main/Cafe%20Sales%20Dashboard.png)
## 🔍 Key Findings
- Salad emerged as the highest-selling item, generating $19,095 in revenue, and clearly establishing itself as the café’s strongest performer.
- Sandwiches and Smoothies followed closely behind, bringing in $14,500 and $13,500 respectively, which highlights their consistent popularity among customers.
- Juice ($11,000) and Cake ($10,000) completed the top five, showing that both refreshing drinks and indulgent desserts contribute meaningfully to overall sales.
- Unknown product entries accounted for more than $4,174 in sales (≈5% of total), which weakens confidence in product-level insights and signals a need for better data capture.
- The peak sales month was June, recording $7,353, driven largely by summer demand and steady customer activity.
- The lowest sales month was February, with $6,644, reflecting a seasonal dip but not a significant drop in overall performance.
- The seasonal variance was only about $700, which demonstrates the café enjoys a stable and loyal customer base throughout the year.
- Unknown values in the date field defaulted to the year 1900, representing missing entries that can distort long-term seasonal or trend analysis if left uncorrected.
## ⚠️ Business Concerns
- Coffee Underperformance: Coffee generated only $7,532 in revenue (8.5% of total), which is unusually low for a café where coffee is typically the anchor product. This weak performance is concerning for the overall business model and suggests that customer demand, product quality, pricing, or marketing around coffee may need immediate review and corrective action.
- Data Quality Gaps: More than $4,174 in unidentified product sales (5%) highlight issues in sales tracking, while unknown payment methods limit visibility into how customers prefer to transact. On top of this, missing location data makes it difficult to assess which channels or outlets are driving performance, creating a blind spot in operational decision-making and reducing confidence in long-term insights.
- Underutilized Categories: Certain menu items are not performing as expected, with cookies contributing only $3,427 and tea also underperforming compared to other beverages. These categories appear underutilized and may require targeted promotions, repositioning in the menu, or even replacement with better-performing items as part of a broader menu optimization strategy.

## 🎯Recommendations
1. Data Quality Recovery  
Improving data quality should be the first step, as inaccurate records undermine every other analysis. Mandatory checkout fields must be enforced to prevent missing entries, while staff should be trained to correctly code products and payment methods. The $4,827 in unidentified product sales requires a thorough audit to understand the source of these discrepancies. Finally, daily monitoring dashboards should be established so errors can be detected and corrected in real time.

2. Product Portfolio Enhancement   
Expanding high-performing categories is an immediate opportunity for growth. Salads, sandwiches, and smoothies already perform well and can be diversified with new flavors or healthier premium options. Introducing seasonal specials can attract customers during traditionally lower-performing months, while premium health-conscious items can tap into growing consumer demand. On the other hand, weaker categories should be phased out or reinvented to keep the menu focused and appealing.

3. Revenue Optimization  
Revenue growth can be achieved through targeted adjustments to pricing and product positioning. Small strategic increases on top-selling categories like salads and sandwiches can lift margins without hurting demand. At the same time, bundling strategies such as pairing a sandwich with a smoothie or salad with coffee can drive higher average order values. Underperforming categories like cookies and tea should either be reduced or refreshed to free up menu space for stronger products. Negotiating better supplier terms can further improve profit margins across the board.

## ✅ Conclusion

The cafe sales analysis highlights both strong opportunities and pressing challenges for the business. While salads, sandwiches, and smoothies drive steady revenue and demonstrate customer loyalty, critical gaps in coffee sales and data quality signal areas requiring urgent attention. By prioritizing accurate data capture, optimizing the product portfolio, and applying smart revenue strategies, the café can strengthen its core offerings, reduce inefficiencies, and unlock untapped potential. Overall, the findings emphasize that consistent data-driven decision-making is essential for sustaining growth and building long-term customer satisfaction.



