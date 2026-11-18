# HR Analytics: Data Quality Audit and Performance Drivers

## Business question
Can employee attributes (age, experience, education, department) explain performance scores?

## Data
Kaggle: Employee Performance Dataset (ziya07). 791 rows, 6 columns. Likely synthetic.

## Approach
1. Data quality audit (duplicates, illogical experience)
2. Descriptive statistics and correlation
3. Average score by department, education level, experience band
4. Dashboard in Looker Studio

## Key findings
- 331 of 791 records (41.8%) have illogical experience (experience > age - 16).
- Average scores are nearly identical across departments (5.29 to 5.72) and education levels (5.24 to 5.76).
- Age and experience have almost no correlation with performance score.

## Recommendation
Add input validation in the HR system and collect more relevant data (workload, training outcomes, job satisfaction).

## Links
- Dashboard: https://datastudio.google.com/reporting/72e9fafd-68b1-42ad-8647-61b8948f33d0
- Spreadsheet: https://docs.google.com/spreadsheets/d/1ZGcoJBxHB3Exb9tJFMyozFPdqkSbSM7vrSNDk9nG1gg
- Dataset (Kaggle) : https://www.kaggle.com/datasets/ziya07/employee-performance-dataset/data

## Limitations
Dataset is likely synthetic, has no time dimension, and correlation does not imply causation.
