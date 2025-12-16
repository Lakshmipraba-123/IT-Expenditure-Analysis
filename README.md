# IT-Expenditure-Analysis

📊 IT Expenditure Variance Analysis (Pandas)
📌 Project Overview

This project analyzes IT expenditure by comparing actual spending against planned budgets to identify variance patterns, cost drivers, and areas requiring optimization. The analysis focuses on understanding when, where, and why IT overspending occurs.

🎯 Objectives

Compare actual IT spend with planned budget

Identify months with high spending variance

Determine high-impact business areas and IT domains

Pinpoint cost elements driving overspending

Provide actionable insights for cost control

📂 Dataset Description

The Excel dataset contains two sheets:

Actuals – Records actual IT expenditure

Budget – Contains planned / budgeted IT spend

Key fields include:

Date (Month-level data)

Business Area

IT Area

Country

Cost Element

Spend Amount

🧹 Data Preparation

Converted month-only data into datetime format for trend analysis

Standardized column names to avoid ambiguity

Handled missing values for accurate variance calculation

📊 Key Analysis & Visualizations

The analysis is built around 5 storytelling charts:

Actual vs Planned IT Spend (Monthly Trend)
Identifies overall spending behavior against budget

Monthly IT Spend Variance
Highlights problem months with overspending

Variance by Business Area
Shows which business units drive IT cost overruns

Variance by Cost Element
Identifies root causes such as licenses, cloud, or services

Variance by IT Area
Establishes accountability within IT domains

🔍 Key Insights

IT spending exceeds planned budgets in multiple months, indicating forecasting gaps

Overspending is concentrated in a few business areas and IT domains

A small set of cost elements contributes to most of the variance

💡 Recommendations

Improve budget forecasting for high-variance months

Introduce tighter monitoring for high-impact business areas

Optimize high-cost elements such as licenses and cloud usage

Establish IT-area-level ownership with monthly variance tracking

🛠 Tools & Technologies

Python

Pandas

Matplotlib

Seaborn

Google Colab

📁 Project Structure
IT-Expenditure-Variance-Analysis/
│
├── IT_Expenditure_Analysis.ipynb
├── IT Expenditure dataset.xlsx
└── README.md

📈 Business Value

This analysis helps organizations:

Gain visibility into IT cost overruns

Improve financial planning and forecasting

Enable data-driven cost optimization decisions

👤 Author

Lakshmi Praba
Data Analytics & Cloud Enthusiast
