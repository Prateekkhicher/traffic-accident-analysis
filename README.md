# 🚗 Traffic Accident Analysis (Python + SQL)

## 📌 Project Overview

This project performs an end-to-end analysis of traffic accident data using Python and SQL to uncover patterns in accident frequency, severity, and contributing risk factors such as time, weather, speed, and driver behavior.
The goal of this analysis is to derive actionable insights that can help improve road safety and support data-driven decision-making.

---

## 🎯 Objectives

- Analyze accident distribution across time, weather, and days
- Understand factors affecting accident severity
- Identify high-risk conditions and patterns
- Perform SQL-based querying to simulate real-world data analysis workflows

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy)
- **Data Visualization** (Matplotlib, Seaborn)
- **SQL** (MySQL)
- **SQLAlchemy** (Database connection)

---

## 📊 Exploratory Data Analysis (EDA)

The dataset was analyzed using Python to explore:

- Accident severity distribution
- Time-of-day accident trends
- Day-of-week patterns
- Weather condition impact
- Driver age and behavior analysis
- Speed vs casualties relationship

---
## 🧠 SQL-Based Analysis

SQL queries were used to validate insights and extract structured patterns:

- Accidents by time category
- Accidents by weather conditions
- Severity distribution
- Average casualties by speed limit
- Alcohol involvement impact
- High-risk combinations (Time + Weather)

---

## 🔑 Key Findings

- Accidents are highest during **night time**, indicating increased risk due to low visibility and fatigue  
- **Rainy and foggy weather** conditions contribute significantly to accident frequency  
- **Higher speed limits** are associated with increased casualties  
- **Alcohol involvement** leads to more severe accidents  
- High-risk scenarios such as **Night + Bad Weather** increase accident probability  

---

## 📁 Project Structure
traffic-accident-analysis/
│
├── traffic_accident_analysis.ipynb # Main analysis (Python + SQL)
├── accident_prediction_india.csv # Raw dataset
├── clean_accident_data.csv # Cleaned dataset
├── requirements.txt # Dependencies
├── README.md # Documentation
└── LICENSE # License

## Conclusion
This project demonstrates how combining Python (EDA + Visualization) with SQL (Data Querying) provides deeper insights into real-world datasets.
The analysis helps identify critical risk factors and can support improvements in road safety policies and decision-making.
