# HR Attrition Analysis | Power BI

An interactive Power BI dashboard built on the IBM HR Analytics dataset, designed to help HR teams understand why employees leave, identify high-risk groups, and take proactive steps to improve retention.

## Project Overview

This dashboard transforms raw HR data into clear, actionable insights through 3 connected report pages, covering 10+ attrition factors, KPI tracking, and a ranked risk-factor summary — all in one place.

## Dashboard Pages

### 1️⃣ Executive Summary

* KPI cards: Total Employees (1,470), Overall Attrition Rate (16.12%)
* Summary table ranking all 10 factors by highest-risk group and attrition rate
* Horizontal bar chart comparing attrition rate across all factors at a glance

### 2️⃣ Tenure & Personal Factors

* Attrition Rate by Years in Current Role
* Attrition Rate by Work-Life Balance
* Attrition Rate by Marital Status
* Attrition Rate by Income Range
* Attrition Rate by Years at Company

### 3️⃣ Demographics & Work Factors

* Attrition Rate by Age Group
* Attrition Rate by Department
* Attrition Rate by Job Satisfaction
* Attrition Rate by Distance from Home
* Attrition Rate by OverTime

## Dashboard Preview

### 1️⃣ Executive Summary
![Executive Summary](Executive%20Summary.PNG)

### 2️⃣ Tenure & Personal Factors
![Tenure and Personal Factors](Tensure%20%26%20Personal%20Factors.PNG)

### 3️⃣ Demographics & Work Factors
![Demographics and Work Factors](Demographics%20and%20Work%20Factors.PNG)

## Tools & Techniques Used

* **Power BI Desktop** — data cleaning, modeling, and report design
* **Power Query** — removed constant/irrelevant columns, fixed data types
* **DAX** — measures (Attrition Rate, Total Employees), calculated columns (Income Range, Age Group, Years at Company Group), SWITCH and IF logic for categorization
* **Sort by Column** — for correct logical ordering of custom categories
* **Data Visualization** — KPI cards, bar charts, summary tables

## Key Insights

* **Compensation is the strongest driver of attrition** — low-income employees show a 56.1% attrition rate, by far the highest of any factor
* **New employees are at the highest risk** — those in their first 0-2 years at the company show ~31% attrition, suggesting onboarding and early engagement are critical
* **Overtime and poor work-life balance correlate strongly with attrition** — overtime workers leave at nearly 3x the rate of non-overtime workers
* **Sales has the highest departmental attrition** (~21%), pointing to potential role-specific pressure

## Recommendations

1. Review compensation structure for entry-level and low-income roles
2. Strengthen onboarding and 90-day check-ins for new hires
3. Revisit overtime policies and workload distribution
4. Investigate Sales department-specific retention strategies (exit interviews, support programs)

## Files in This Repository

* `HR_Attrition_Analysis.pbix` — Power BI project file
* `Executive Summary.PNG`, `Tensure & Personal Factors.PNG`, `Demographics and Work Factors.PNG` — Dashboard preview images
* `README.md` — Project documentation

## Connect

* LinkedIn: [your-linkedin-url]
* GitHub: [github.com/Hadia3112](https://github.com/Hadia3112)

⭐ If you found this project useful, feel free to star this repository!


## How It Was Built

- Cleaned data using Power Query (removed constant columns, handled data types)
- Created DAX measures (Attrition Rate, Total Employees)
- Built conditional/calculated columns to group continuous data (Income, Age, Tenure)
- Designed a 3-page dashboard: Executive Summary, and detailed factor breakdowns
