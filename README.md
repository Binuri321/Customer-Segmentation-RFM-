# Customer Segmentation using RFM Analysis

# Introduction
This project applies RFM (Recency, Frequency, Monetary) analysis to an e-commerce dataset to identify distinct customer segments. The goal is to help businesses understand who their most valuable customers are, detect customers at risk of churn, and uncover opportunities for targeted marketing strategies. By segmenting customers based on their purchase behavior, companies can tailor their engagement efforts to boost loyalty and revenue.

# Dataset Information
- Source: E-commerce transactional data containing customer purchases.
- Contents: Customer key, Geography key, Customer Alternate key, title,name,birthday,	MaritalStatus	,	Gender,	EmailAddress,	YearlyIncome	etc.
- Purpose: To calculate recency (days since last purchase), frequency (number of purchases), and monetary value (total spent) for each customer.

# Business Problem
- Identify loyal and high-value customers for retention and rewards.
- Detect at-risk and inactive customers who may churn.
- Provide actionable insights to marketing and sales teams for personalized campaigns.

# Data Cleaning
- Used Microsoft Excel for initial data cleaning and calculation of total price per transaction.
- Steps included removing duplicates, handling missing values, and formatting date fields.
- Ensured consistent data types for smooth import into Power BI.

# Analysis
- Imported cleaned data into Power BI.
- Created RFM scoring logic using DAX formulas:
  - Recency: Calculated as the number of days since the last purchase.
  - Frequency: Counted total purchases per customer.
  - Monetary: Summed total spending per customer.
- Assigned scores (1 to 5) for each RFM metric to classify customers.

# Visualizations
- KPI Cards: Display total no of customers and total sales.
- Bar Charts & Pie Charts: Show total sales by gender and marital status
- Top Customers Table: Interactive table with sortable insights on customer value.
- Slicers: Allow filtering by product name.

## Key Findings
- A small percentage of customers (Champions) contribute a large portion of revenue.
- Several customers are identified as at-risk or inactive, representing opportunities for re-engagement.
- Different customer segments respond differently to marketing efforts, highlighting the need for targeted campaigns.

# Business Recommendations
- Focus marketing resources on retaining Champions and Loyal customers through loyalty programs and exclusive offers.
- Design re-engagement campaigns for At-Risk customers to reduce churn.
- Personalize promotions based on customer segments to maximize ROI.
- Continuously monitor RFM scores to adapt strategies as customer behavior changes.

# Credits
- Tools used: Microsoft Excel, Power BI, DAX.

