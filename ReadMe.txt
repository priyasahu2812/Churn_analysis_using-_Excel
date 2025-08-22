 Telecom Customer Churn Analysis

Overview
This project analyzes telecom customer churn using Excel to identify patterns, calculate churn rates, and visualize insights with interactive dashboards.

The goal is to:
- Calculate and monitor customer churn rate.
- Identify which customer segments (age, demographics, data usage) have the highest churn.
- Understand key churn reasons and competitor impact.
- Present KPIs and insights in a structured dashboard.

---

Project Steps
1. Data Cleaning & Preparation
   - Removed duplicates and standardized columns.
   - Created new calculated fields: `Churned`, `Demographics`, `Grouped Consumption`.
2. Exploratory Data Analysis
   - Analyzed churn rate by state, age, demographics, plan type, and data usage.
   - Created PivotTables and calculated churn rate KPIs.
3. Visualization & Dashboarding
   - Built stacked bar, column, and combo charts.
   - Developed an Overview dashboard summarizing:
     - Total customers, churned customers, churn rate.
     - Churn by reason and competitor.
     - Churn by demographics and age.
     - Churn by data plan and consumption.
     - Top 25 states by churn rate.

---

Key Insights
- Overall churn rate: ~26.86%
- Highest churn reasons: Competitor-related issues and price dissatisfaction.
- Senior and under-30 demographics show higher churn rates than other groups.
- Unlimited data plans correlate with lower churn for high consumption users.
- Certain states with international plan users have exceptionally high churn rates.

---

Dashboard Preview
![Churn Dashboard](images/dashboard_preview.png)

---

Files in this Repository
- `Churn_Analysis.xlsx` – Complete analysis workbook with pivots and dashboard.
- `Customers.csv` / `Aggregate.csv` – Source datasets (if shareable).
- `/images` – Screenshots of the dashboard and visualizations.
- `README.md` – Project documentation.

---

Tools Used
- Microsoft Excel:PivotTables, Calculated Fields, Conditional Formatting.
- Visualization: Stacked bar charts, combo charts, dashboards.

---

How to Use
1. Download `Churn_Analysis.xlsx`
2. Explore the `Churn Analysis` and `Overview` sheets.
3. Modify or refresh PivotTables to update calculations if new data is added.

---

Author
Priya Sahu – B.Tech CSE (AI) Student | Data Analytics Enthusiast  
Connect with me on [LinkedIn](http://www.linkedin.com/in/priyasahu12)
