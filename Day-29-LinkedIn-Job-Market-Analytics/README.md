# 💼 Day 29/30 — LinkedIn Job Market Analytics Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![DAX](https://img.shields.io/badge/DAX-Calculations-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Cleaning-green)
![Challenge](https://img.shields.io/badge/30%20Days-30%20Dashboards-orange)

## 📊 Project Overview

This is **Day 29** of my **30 Days, 30 Dashboards Challenge**.

In this project, I created a **LinkedIn Job Market Analytics Dashboard using Power BI** to analyze job postings, job roles, locations, industries, experience levels, employment types, and hiring trends.

The objective is to transform job market data into meaningful insights using interactive dashboards and data visualization.

---

## 🎯 Business Problem

The job market contains a large amount of information about job roles, companies, locations, experience levels, industries, and employment types.

This dashboard helps analyze questions such as:

- Which job roles have the most openings?
- Which locations have higher job demand?
- Which industries are hiring more?
- What experience levels are most in demand?
- What are the most common employment types?
- Which skills/job categories are frequently requested?
- How is job demand distributed across locations?

---
<img width="2880" height="1692" alt="Screenshot 2026-09-30 095153" src="https://github.com/user-attachments/assets/67ff1ece-7c4a-4be8-b6f6-fdf152027f9c" />

## 🎯 Project Objectives

- Analyze job posting trends
- Identify high-demand job roles
- Analyze job opportunities by location
- Compare industries
- Analyze experience levels
- Study employment types
- Identify hiring patterns
- Create interactive KPIs
- Support data-driven job market analysis

---

## 📌 Key KPIs

- 💼 Total Job Postings
- 🏢 Total Companies
- 📍 Total Locations
- 👨‍💻 Total Job Roles
- 🏭 Total Industries
- 📊 Average Jobs per Company
- 🎯 Entry-Level Jobs
- 💼 Full-Time Jobs
- 🌍 Jobs by Location

---

## 📈 Dashboard Features

### 💼 Job Role Analysis

- Job postings by role
- Most demanded job titles
- Role-wise job distribution
- Job category analysis

### 📍 Location Analysis

- Jobs by country/city
- Location-wise job demand
- Top hiring locations
- Geographic distribution

### 🏭 Industry Analysis

- Jobs by industry
- Industry-wise hiring demand
- Top hiring sectors

### 🎓 Experience Analysis

- Entry-level jobs
- Mid-level jobs
- Senior-level jobs
- Experience-wise job distribution

### 🕒 Employment Type Analysis

- Full-time
- Part-time
- Contract
- Internship
- Other employment types

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

Steps included:

- Removing duplicate job postings
- Handling missing values
- Cleaning job titles
- Standardizing locations
- Correcting data types
- Cleaning industry categories
- Transforming experience-level fields
- Creating analysis-ready columns

---

## 🧮 DAX Calculations

Example measures used in the dashboard:

```DAX
Total Job Postings =
COUNTROWS('LinkedIn Job Data')
Total Companies =
DISTINCTCOUNT('LinkedIn Job Data'[Company])
Total Locations =
DISTINCTCOUNT('LinkedIn Job Data'[Location])
Total Job Roles =
DISTINCTCOUNT('LinkedIn Job Data'[Job Title])
Average Jobs per Company =
DIVIDE(
    [Total Job Postings],
    [Total Companies]
)
📊 Visualizations

The dashboard includes:

KPI Cards
Bar Charts
Column Charts
Donut Charts
Line Charts
Tables
Location analysis
Job role analysis
Industry analysis
Interactive slicers
🎛️ Filters / Slicers

Users can filter the dashboard by:

Job Title
Location
Industry
Experience Level
Employment Type
Company
Job Category
💡 Key Insights

The dashboard helps identify:

High-demand job roles
Locations with more opportunities
Industries with higher hiring activity
Experience levels in demand
Employment type distribution
Company-wise hiring patterns
Job market trends
🚀 Business Impact

Job market analytics can help:

Job seekers understand market demand
Identify popular job roles
Understand location-wise opportunities
Analyze industry hiring trends
Understand experience requirements
Support data-driven career planning
🛠️ Tools & Technologies
Power BI
DAX
Power Query
Microsoft Excel
Data Cleaning
Data Visualization
Business Intelligence
🖼️ Dashboard Preview
<p align="center"> <img src="LinkedIn-Job-Market-Analytics-Dashboard.png" alt="LinkedIn Job Market Analytics Dashboard" width="100%"> </p>
📂 Project Structure
Day-29-LinkedIn-Job-Market-Analytics/
│
├── README.md
├── LinkedIn-Job-Market-Analytics.pbix
├── LinkedIn-Job-Market-Dataset.xlsx
└── LinkedIn-Job-Market-Analytics-Dashboard.png
📅 30 Days, 30 Dashboards Challenge
🔥 Day 29/30 Completed!

Progress:

█████████████████████████████░ 29/30

Only 1 dashboard remaining! 🚀

Through this challenge, I am strengthening my practical skills in:

Data Analytics
Power BI
DAX
Power Query
Data Visualization
Business Intelligence
Business Problem Solving
👨‍💻 Author

Abhishek Kashyap

Aspiring Data Analyst | Power BI | SQL | Python | Data Analytics

GitHub:

https://github.com/abhishekkashyap78

🏷️ Tags

#PowerBI #LinkedInAnalytics #JobMarketAnalytics #JobMarket
#DataAnalytics #DataAnalyst #DAX #PowerQuery
#DataVisualization #BusinessIntelligence #PowerBIDashboard
#30Days30Dashboards #Dashboard #OpenToWork #JobSearch


### 🔥 GitHub Commit

**Commit message:**
```text
Day 29: Added LinkedIn Job Market Analytics Dashboard

Repository description:

💼 LinkedIn Job Market Analytics Dashboard built with Power BI | Day 29 of 30 Days, 30 Dashboards Challenge.
