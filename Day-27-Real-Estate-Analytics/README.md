# 🏠 Day 27 — Real Estate Analytics Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue)
![DAX](https://img.shields.io/badge/DAX-Calculations-orange)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)

## 📌 Overview

This project is part of my **30 Days • 30 Dashboards Challenge**, where I build one interactive Power BI dashboard every day.

For Day 27, I created a **Real Estate Analytics Dashboard** using Power BI to analyze property sales, property prices, locations, property types, sales trends, customer demand, and overall real estate performance.

The dashboard provides an interactive view of real estate data to support data-driven property and business decisions.

---

## 🎯 Business Problem

Real estate businesses need to understand property demand, pricing, sales performance, and location-wise trends to make better decisions.

Key questions include:

- How many properties were sold?
- What is the total sales value?
- Which locations have higher property demand?
- Which property types perform better?
- What is the average property price?
- How do property prices vary by location?
- Which areas generate higher sales?
- What are the sales trends over time?

This dashboard helps answer these questions through interactive visualizations.

---

## 🎯 Project Objectives

- Analyze overall property sales
- Monitor total sales value
- Analyze property prices
- Compare property types
- Analyze location-wise performance
- Identify high-demand areas
- Study sales trends over time
- Analyze average property price
- Compare property sizes
- Support data-driven real estate decisions

---

## 📊 Key KPIs

The dashboard includes:

- 🏠 Total Properties
- 🏷️ Properties Sold
- 💰 Total Sales Value
- 💵 Average Property Price
- 📊 Median Property Price
- 📍 Total Locations
- 🏘️ Total Property Types
- 📐 Average Property Size
- 📈 Sales Growth
- 🧾 Average Price per Sq. Ft.

---

## 🔍 Dashboard Features

### 🏠 Property Analysis

- Total property inventory
- Sold vs available properties
- Property type distribution
- Property size analysis
- Property price analysis

### 📍 Location Analysis

- Location-wise property sales
- Location-wise average price
- High-performing areas
- Property demand by location

### 💰 Price Analysis

- Average property price
- Price distribution
- Price by property type
- Price by location
- Price per square foot

### 📈 Sales Trend Analysis

- Monthly sales trends
- Yearly sales trends
- Property sales growth
- Revenue trends

### 🏘️ Property Type Analysis

- Apartments
- Houses
- Villas
- Commercial properties
- Other property categories

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

Steps included:

- Removing duplicate records
- Handling missing values
- Correcting data types
- Cleaning column names
- Standardizing property categories
- Standardizing location names
- Creating calculated columns
- Preparing data for Power BI analysis

---

## 🧮 DAX Calculations

Example measures used:
Sold Properties =
CALCULATE(
    COUNTROWS('Real Estate Data'),
    'Real Estate Data'[Status] = "Sold"
)
Total Sales Value =
SUM('Real Estate Data'[Sale Price])
Average Property Price =
AVERAGE('Real Estate Data'[Sale Price])
Average Property Size =
AVERAGE('Real Estate Data'[Property Size])
Average Price per Sq Ft =
DIVIDE(
    [Total Sales Value],
    SUM('Real Estate Data'[Property Size])
)
Sales Rate =
DIVIDE(
    [Sold Properties],
    [Total Properties]
)
📈 Visualizations

The dashboard contains:

KPI Cards
Property Sales Overview
Sold vs Available Properties
Sales by Location
Average Price by Location
Property Type Distribution
Price Analysis
Property Size Analysis
Monthly Sales Trend
Sales Value Trend
Price per Sq. Ft. Analysis
🎛️ Filters / Slicers

The dashboard can be filtered by:

Property Type
Location
Property Status
Price Range
Property Size
Date
Bedrooms
Customer Segment
💡 Key Insights

The dashboard helps identify:

🏠 Overall property sales performance

💰 High-value property segments

📍 Locations with higher property demand

🏘️ Popular property types

📊 Property price distribution

📐 Relationship between property size and price

📈 Sales trends over time

🎯 Areas with stronger real estate performance

🚀 Business Impact

Real estate analytics can help businesses:

Identify high-demand locations
Understand property pricing
Monitor sales performance
Optimize property listings
Identify high-performing property types
Improve pricing strategies
Understand customer demand
Support investment decisions
Make data-driven business decisions
🛠️ Tools & Technologies
Power BI
DAX
Power Query
Microsoft Excel
Data Visualization
Data Analytics
Business Intelligence
🧠 Skills Demonstrated
Data Cleaning
Data Transformation
Data Modeling
DAX
KPI Development
Real Estate Analytics
Sales Analysis
Location Analysis
Price Analysis
Data Visualization
Business Intelligence
Business Problem Solving
🖼️ Dashboard Preview
<img width="2880" height="1692" alt="d27" src="https://github.com/user-attachments/assets/9bec5f93-c1e9-4994-8135-20e15c46afb6" />

📁 Project Structure
Day-27-Real-Estate-Analytics/
│
├── README.md
├── Real-Estate-Analytics.pbix
├── Real-Estate-Dataset.xlsx
└── Real-Estate-Analytics-Dashboard.png
🎯 30 Days • 30 Dashboards Challenge
Day 27/30 🔥

27 dashboards completed!

This challenge focuses on improving practical skills in:

Power BI | DAX | Power Query | Data Analytics | Data Visualization | Business Intelligence

Only 3 dashboards remaining! 🚀

👨‍💻 Author

Abhishek Kashyap

B.Tech CSE (AI/ML)
Aspiring Data Analyst

Skills: Power BI | SQL | Python | Excel | DAX | Data Analytics

🔗 Connect

GitHub:
https://github.com/abhishekkashyap78

#PowerBI #RealEstateAnalytics #RealEstate #PropertyAnalytics #DataAnalytics #DataAnalyst #DAX #PowerQuery #BusinessIntelligence #DataVisualization #PowerBIDashboard #30Days30Dashboards #Dashboard #RealEstateData


## 📤 GitHub Upload Order

Folder ke andar ye **4 files** upload kar:

1. `README.md`
2. `Real-Estate-Analytics.pbix`
3. `Real-Estate-Dataset.xlsx`
4. `Real-Estate-Analytics-Dashboard.png`

### 🔥 Progress
**27/30 Dashboards Completed — Only 3 Remaining! 🚀**

```DAX
Total Properties =
COUNTROWS('Real Estate Data')
