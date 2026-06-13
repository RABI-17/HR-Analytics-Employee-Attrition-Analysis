# HR Analytics: Employee Attrition Analysis

![Dashboard Preview](dashboard.png)

## Overview
SQL-driven analysis of 1,470 IBM employees across 35 dimensions
to identify key attrition drivers and build a composite risk model
that predicts employee flight risk with actionable HR recommendations.

## Live Dashboard
🔗 [Tableau Public Dashboard] (https://public.tableau.com/app/profile/rabinarayan.sahu/viz/IBMHRAttritionAnalysis_17812941961080/Dashboard1)

## Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- SQL (SQLite — window functions, CTEs, CASE WHEN)
- Tableau Public
- Power BI Desktop
- Google Colab
- Dataset: IBM HR Analytics Employee Attrition (Kaggle)

## Key Findings
1. Overall attrition rate: [X]% — above 10–15% industry benchmark
2. Overtime employees leave at 3x the rate of non-overtime employees
3. Sales has the highest department attrition at [X]%
4. Employees with all 4 risk factors show ~80% attrition rate
5. Manager stability is a hidden retention lever — longer time
   with the same manager strongly predicts lower attrition

## Project Structure
```
hr-analytics-attrition/
├── hr_attrition_analysis.ipynb   # main analysis notebook
├── hr_clean1.csv                  # cleaned dataset
├── dashboard1.png                 # Tableau dashboard screenshot
└── README.md
```

## New SQL Skills Used
- CASE WHEN for conditional aggregation
- RANK() OVER (PARTITION BY) window functions
- CTEs (Common Table Expressions) for multi-step queries
- Composite risk scoring model in pure SQL

## How to Run
1. Open `hr_attrition_analysis.ipynb` in Google Colab
2. Upload `hr_clean1.csv` when prompted
3. Run all cells in order

## Connect
[LinkedIn](www.linkedin.com/in/rabi-narayan-sahu) | [GitHub Portfolio](https://github.com/RABI-17)
