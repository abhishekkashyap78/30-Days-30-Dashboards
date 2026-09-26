# 🏦 Day 26 — Loan & Banking Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue)
![DAX](https://img.shields.io/badge/DAX-Calculations-orange)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)

## 📌 Overview

This project is part of my **30 Days • 30 Dashboards Challenge**, where I build one interactive Power BI dashboard every day.

For Day 26, I created a **Loan & Banking Analysis Dashboard** using Power BI to analyze loan applications, approved and rejected loans, loan amounts, customer segments, repayment behavior, interest rates, and overall banking performance.

The dashboard provides an interactive view of loan and customer data to support data-driven banking decisions.

---

## 🎯 Business Problem

Banks and financial institutions need to continuously monitor their loan portfolio and customer activity.

They need to understand:

- How many loan applications are received?
- How many loans are approved or rejected?
- What is the total loan amount?
- Which customer segments apply for more loans?
- Which loan types have higher demand?
- What is the average interest rate?
- How does loan status vary across customer segments?
- What factors are associated with loan performance?

This dashboard helps analyze these areas through interactive visualizations.

---

## 🎯 Project Objectives

- Analyze total loan applications
- Monitor approved and rejected loans
- Analyze total loan amount
- Calculate approval rate
- Analyze loan types
- Study customer segments
- Analyze interest rates
- Monitor repayment behavior
- Compare loan performance
- Identify important banking trends

---

## 📊 Key KPIs

The dashboard includes:

- 📝 Total Loan Applications
- ✅ Approved Loans
- ❌ Rejected Loans
- 💰 Total Loan Amount
- 📊 Approval Rate
- 💵 Average Loan Amount
- 📈 Average Interest Rate
- 👥 Total Customers
- 💳 Active Loans
- 💰 Total Repayment Amount

---

## 🔍 Dashboard Features

### 📝 Loan Application Analysis

- Total loan applications
- Approved vs rejected applications
- Application trends
- Loan status analysis

### 💰 Loan Amount Analysis

- Total loan amount
- Average loan amount
- Loan amount by loan type
- Loan amount by customer segment

### 👥 Customer Analysis

- Customer distribution
- Customer segment analysis
- Income-based analysis
- Customer-wise loan activity

### 📊 Loan Type Analysis

- Personal loans
- Home loans
- Education loans
- Business loans
- Other loan categories

### 💳 Repayment Analysis

- Repayment amount
- Loan repayment status
- Active vs completed loans
- Customer repayment behavior

### 📈 Interest Rate Analysis

- Average interest rate
- Interest rate by loan type
- Interest rate comparison across customer segments

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
- Preparing data for Power BI analysis

---

## 🧮 DAX Calculations

Example measures used:

```DAX
Total Applications =
COUNTROWS('Loan Banking Data')
Approved Loans =
CALCULATE(
    COUNTROWS('Loan Banking Data'),
    'Loan Banking Data'[Loan Status] = "Approved"
)
Rejected Loans =
CALCULATE(
    COUNTROWS('Loan Banking Data'),
    'Loan Banking Data'[Loan Status] = "Rejected"
)
Total Loan Amount =
SUM('Loan Banking Data'[Loan Amount])
Approval Rate =
DIVIDE(
    [Approved Loans],
    [Total Applications]
)
Average Loan Amount =
AVERAGE('Loan Banking Data'[Loan Amount])
Average Interest Rate =
AVERAGE('Loan Banking Data'[Interest Rate])
📈 Visualizations

The dashboard contains:

KPI Cards
Loan Application Overview
Approved vs Rejected Loans
Loan Amount Analysis
Loan Type Analysis
Customer Segment Analysis
Interest Rate Analysis
Repayment Analysis
Loan Status Distribution
Time-based Trends
🎛️ Filters / Slicers

The dashboard can be filtered by:

Loan Type
Loan Status
Customer Segment
Gender
Age Group
Income Category
Location
Application Date
Repayment Status
💡 Key Insights

The dashboard helps identify:

📊 Overall loan application performance

✅ Approval and rejection patterns

💰 Loan amount distribution

👥 Customer segments with higher loan activity

🏦 Loan types with higher demand

📈 Interest rate patterns

💳 Repayment behavior

📅 Loan application trends over time

🚀 Business Impact

Loan and banking analytics can help financial institutions:

Monitor loan portfolio performance
Understand customer borrowing behavior
Improve loan approval processes
Identify high-demand loan products
Monitor repayment patterns
Improve risk monitoring
Support better customer segmentation
Make data-driven banking decisions
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
Banking Analytics
Loan Analysis
Customer Analytics
Data Visualization
Business Intelligence
Business Problem Solving
🖼️ Dashboard Preview
<img width="2880" height="1692" alt="d25" src="https://github.com/user-attachments/assets/56f88d38-ca69-48e4-81dc-a3c8791cf06e" />

Day-26-Loan-and-Banking-Analysis/
│
├── README.md
├── Loan-and-Banking-Analysis.pbix
├── Loan-and-Banking-Dataset.xlsx
└── Loan-and-Banking-Dashboard.png
🎯 30 Days • 30 Dashboards Challenge
Day 26/30 🔥

26 dashboards completed!

This challenge focuses on improving practical skills in:

Power BI | DAX | Power Query | Data Analytics | Data Visualization | Business Intelligence

Only 4 dashboards remaining! 🚀

👨‍💻 Author

Abhishek Kashyap

B.Tech CSE (AI/ML)
Aspiring Data Analyst

Skills: Power BI | SQL | Python | Excel | DAX | Data Analytics

🔗 Connect

GitHub:
https://github.com/abhishekkashyap78

#PowerBI #BankingAnalytics #LoanAnalysis #DataAnalytics #DataAnalyst #DAX #PowerQuery #Banking #FinancialAnalytics #BusinessIntelligence #DataVisualization #PowerBIDashboard #30Days30Dashboards #Dashboar
