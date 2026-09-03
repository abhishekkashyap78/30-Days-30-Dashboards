🏏 IPL Analysis Dashboard – Power BI Project
📊 Project Overview

This project focuses on analyzing Indian Premier League (IPL) data using Power BI to uncover insights about teams, players, and match performances.
The dashboard provides a visual representation of IPL trends, including top players, winning teams, venues, and season statistics.

🎯 Objectives

To explore IPL data and identify performance trends.

To create an interactive Power BI dashboard for better visualization.

To analyze team performance, player statistics, and match outcomes.

To derive data-driven insights that could help understand key success factors.

📁 Dataset

Source: Kaggle / official IPL dataset

Files Used:

matches.csv – Match-level details (venue, date, winner, toss result, etc.)

deliveries.csv – Ball-by-ball data (batsman, bowler, runs, wickets, etc.)

🧹 Data Cleaning & Preparation

Removed missing and duplicate entries.

Renamed columns for clarity.

Created calculated columns like:

Total Runs per Player

Strike Rate, Average, and Economy Rate

Win Percentage by Team

Merged datasets (matches and deliveries) using match_id.

📈 Dashboard Features

Main Pages / Tabs:

Overview Dashboard

Total Matches, Teams, Seasons, and Players

Top 5 Teams by Wins

Toss Decisions and Results

Team Analysis

Win/Loss record by season

Performance by venue

Toss vs Match win relation

Player Analysis

Top Batsmen (Runs, Strike Rate)

Top Bowlers (Wickets, Economy Rate)

Player of the Match insights

Season Insights

Year-wise team standings

Most successful teams

Venue impact analysis

🛠️ Tools & Technologies

Power BI Desktop – Data visualization

Microsoft Excel / Power Query – Data cleaning

DAX (Data Analysis Expressions) – Calculations and KPIs

Kaggle Dataset – Data source

💡 Key Insights

Teams winning the toss do not always win the match.

Certain venues favor chasing teams.

Consistent top performers across seasons include Virat Kohli, AB de Villiers, and Lasith Malinga.

Mumbai Indians and Chennai Super Kings show the highest win percentages.

📸 Dashboard Preview
![Uploading Screenshot 2026-09-03 104321.png…]()


🚀 How to Use

Download the .pbix file from this repository.

Open it in Power BI Desktop.

Refresh the data connections (if necessary).

Interact with filters and visuals to explore insights.

📚 Future Improvements

Add predictive analysis (e.g., match winner prediction).

Automate data refresh from API sources.

Include real-time Power BI service dashboard.

👨‍💻 Author

Abhishek Kashyap
