# HR Employee Attrition Analysis

End-to-end HR analytics project analyzing 1,470 employee records to identify attrition drivers.

## Business Question
Why are employees leaving, and where is attrition concentrated?

## Approach
1. **Data Validation (Python/Pandas)** — Confirmed 1,470 clean rows with zero missing values and zero duplicates.
2. **SQL Analysis (MySQL)** — Queried attrition rates by department, job role, and overtime status using GROUP BY and conditional aggregation.
3. **Dashboard (Power BI)** — Built an interactive dashboard with KPI cards and category-level color highlighting to surface risk areas.

## Key Findings
- **Overtime nearly triples attrition risk:** 30.53% attrition among employees working overtime vs. 10.44% for those who don't.
- **Sales Representative has the highest attrition of any role:** 39.76% — more than double the company average.
- **Overall attrition rate:** 16.12% (237 of 1,470 employees).
- Employees who left earned $4,787/month on average vs. $6,833 for those who stayed, and had shorter average tenure (5.13 vs. 7.37 years).

## Tools Used
Python (Pandas), SQL (MySQL), Power BI (DAX, conditional formatting)

## Dataset
IBM HR Analytics Employee Attrition dataset (Kaggle)

## Dashboard Preview
*(screenshot link goes here — see below)*
