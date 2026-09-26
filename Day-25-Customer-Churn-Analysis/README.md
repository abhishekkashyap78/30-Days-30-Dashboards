# 📊 Day 25 — Customer Churn Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue)
![DAX](https://img.shields.io/badge/DAX-Calculations-orange)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)

## 📌 Overview

This project is part of my **30 Days • 30 Dashboards Challenge**, where I build one interactive Power BI dashboard every day.

For Day 25, I created a **Customer Churn Analysis Dashboard** to analyze customer retention, churn behavior, customer segments, tenure, contracts, payment methods, and revenue patterns.

The dashboard helps identify customer groups with higher churn and provides insights that can support customer retention strategies.

---

## 🎯 Business Problem

Customer churn is an important business problem because losing customers can directly impact revenue and long-term growth.

Businesses need to understand:

- How many customers are leaving?
- What is the overall churn rate?
- Which customer segments have higher churn?
- Does customer tenure affect churn?
- Which contract types have higher churn?
- Which payment methods are associated with churn?
- Which customers may be at higher risk?

This dashboard provides a visual and interactive way to analyze these questions.

---

## 🎯 Project Objectives

- Analyze overall customer churn
- Calculate churn rate
- Compare churned and retained customers
- Analyze customer tenure
- Analyze contract types
- Compare payment methods
- Analyze customer segments
- Study revenue patterns
- Identify high-risk customer groups
- Provide actionable business insights

---
<img width="2880" height="1692" alt="d25" src="https://github.com/user-attachments/assets/ef09074b-b74a-4f60-b405-9297df45579f" />

## 📊 Key KPIs

The dashboard includes important KPIs such as:

- 👥 Total Customers
- 📉 Churned Customers
- 📈 Retained Customers
- 📊 Churn Rate
- 💰 Total Revenue
- 💵 Average Revenue
- ⏳ Average Customer Tenure
- 📋 Total Contracts
- 🔄 Retention Rate

---

## 🔍 Dashboard Features

### 👥 Customer Analysis
- Total customer count
- Churned vs retained customers
- Customer segmentation
- Customer tenure analysis

### 📉 Churn Analysis
- Overall churn rate
- Churn by customer segment
- Churn by tenure
- Churn by contract type
- Churn by payment method

### 💰 Revenue Analysis
- Revenue contribution
- Average customer revenue
- Revenue from retained customers
- Revenue impact of churn

### 📊 Contract Analysis
- Monthly contracts
- Yearly contracts
- Contract-wise churn comparison

### 💳 Payment Analysis
- Payment method distribution
- Churn by payment method
- Customer behavior by payment type

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

Steps included:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Cleaning column names
- Standardizing categorical values
- Creating calculated columns
- Preparing data for analysis

---

## 🧮 DAX Calculations

Example measures used in the dashboard:
Churned Customers =
CALCULATE(
    COUNTROWS('Customer Churn Data'),
    'Customer Churn Data'[Churn] = "Yes"
)
Retained Customers =
CALCULATE(
    COUNTROWS('Customer Churn Data'),
    'Customer Churn Data'[Churn] = "No"
)
Churn Rate =
DIVIDE(
    [Churned Customers],
    [Total Customers]
)
Retention Rate =
DIVIDE(
    [Retained Customers],
    [Total Customers]
)
Total Revenue =
SUM('Customer Churn Data'[Revenue])
📈 Visualizations

The dashboard contains interactive visuals such as:

KPI Cards
Churn Rate Card
Churned vs Retained Customers
Churn by Contract Type
Churn by Payment Method
Churn by Customer Segment
Churn by Tenure
Revenue Analysis
Customer Distribution Charts
Trend Analysis
🎛️ Filters / Slicers

Users can interact with the dashboard using filters such as:

Contract Type
Payment Method
Customer Segment
Gender
Tenure
Churn Status
Customer Category
💡 Key Insights

The dashboard can help identify:

📉 Customer segments with higher churn rates

👥 Differences between retained and churned customers

📋 Contract types associated with higher churn

💳 Payment methods with different churn patterns

⏳ Relationship between customer tenure and churn

💰 Potential revenue impact from customer churn

🎯 High-risk customer groups that may require retention efforts

🚀 Business Impact

Customer churn analysis can help businesses:

Identify customers at risk of leaving
Improve customer retention
Develop targeted retention campaigns
Understand customer behavior
Reduce potential revenue loss
Improve customer experience
Support data-driven decision making
🛠️ Tools & Technologies
Power BI
DAX
Power Query
Microsoft Excel
Data Visualization
Data Analytics
🧠 Skills Demonstrated
Data Cleaning
Data Transformation
Data Modeling
DAX
KPI Development
Customer Analytics
Churn Analysis
Business Intelligence
Data Visualization
Business Problem Solving
🖼️ Dashboard Preview
<img width="2880" height="1692" alt="image" src="https://github.com/user-attachments/assets/a53c373b-0009-44e1-906e-938bdefa42b1" />

Day-25-Customer-Churn-Analysis/
│
├── README.md
├── Customer-Churn-Analysis.pbix
├── Customer-Churn-Dataset.xlsx
└── Customer-Churn-Dashboard.png
🎯 30 Days • 30 Dashboards Challenge

Day 25/30 🔥

25 dashboards completed!

The challenge focuses on building practical Power BI dashboards while improving skills in:

Power BI | DAX | Power Query | Data Analytics | Data Visualization | Business Intelligence

Only 5 dashboards remaining! 🚀

👨‍💻 Author

Abhishek Kashyap

B.Tech CSE (AI/ML)
Aspiring Data Analyst

Skills: Power BI | SQL | Python | Excel | DAX | Data Analytics

🔗 Connect

GitHub:
https://github.com/abhishekkashyap78

#PowerBI #CustomerChurn #ChurnAnalysis #DataAnalytics #DataAnalyst #DAX #PowerQuery #CustomerAnalytics #BusinessIntelligence #DataVisualization #30Days30Dashboards #Dashboard #PowerBIDashboard

```DAX
Total Customers =
COUNTROWS('Customer Churn Data')
