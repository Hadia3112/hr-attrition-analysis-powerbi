# HR Analytics: Employee Attrition & Performance Analysis

A Power BI dashboard analyzing employee attrition across 10+ factors to help HR teams identify retention risks and take proactive action.

## Project Overview

This project uses the IBM HR Analytics Employee Attrition dataset to explore why employees leave a company, and which factors most strongly predict attrition. The goal is to translate raw HR data into clear, actionable insights for decision-makers.

**Tool used:** Power BI (Power Query, DAX, Data Visualization)
**Dataset:** [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) (Kaggle)

## Objective

- End User: HR Managers / Department Heads
- Goal: Identify key factors driving employee attrition and provide actionable recommendations to improve retention
- Data Type: Mix of factual data (income, age) and survey-based perception data (job satisfaction, work-life balance)

## Key Findings

| Factor | Highest Risk Group | Attrition Rate |
|---|---|---|
| Monthly Income | Low | 56.1% |
| Work-Life Balance | Bad | 31.25% |
| Years at Company | 0-2 (New) | ~31% |
| OverTime | Yes | 30.5% |
| Age Group | 18-25 | ~30% |
| Marital Status | Single | 25.5% |
| Job Satisfaction | Low | 23% |
| Department | Sales | ~21% |
| Distance from Home | 15+ km | 20.67% |
| Years in Current Role | 0-2 (New to Role) | ~19% |

Overall Attrition Rate: 16.12%

## Top Recommendations

1. Strengthen onboarding — new employees (0-2 years) show the highest attrition; early engagement programs could help.
2. Review compensation — low-income employees show dramatically higher attrition.
3. Address overtime/burnout — overtime workers leave at 3x the rate of others.
4. Sales department retention strategy — highest attrition by department; exit interviews recommended.

## Dashboard Preview
### Executive Summary
![Executive Summary](Executive_Summary.PNG)

### Page 1: Tenure & Personal Factors
![Tenure and Personal Factors](Tensure___Personal_Factors.PNG)

### Page 2: Demographics & Work Factors
![Demographics and Work Factors](Demographics_and_Work_Factors.PNG)


## How It Was Built

- Cleaned data using Power Query (removed constant columns, handled data types)
- Created DAX measures (Attrition Rate, Total Employees)
- Built conditional/calculated columns to group continuous data (Income, Age, Tenure)
- Designed a 3-page dashboard: Executive Summary, and detailed factor breakdowns

## Files

- HR_Attrition_Analysis.pbix — Power BI file
