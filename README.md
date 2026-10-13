# HR-Analytics-Dashboard-Excel-
Why do people leave a company, and who are the people who stay?
# HR Analytics Dashboard (Excel)

*Why do people leave a company, and who are the people who stay?*

An interactive HR dashboard built entirely in Excel, using pivot tables, pivot charts and slicers on a dataset of **1,470 employees**.

![HR Analytics Dashboard](images/dashboard.png)

---

## What this project does

HR teams track attrition, headcount and employee satisfaction every month. This dashboard puts those numbers on one screen and lets you filter them by **gender** and **education field**.

## Dashboard view (as saved in the file)

The Education Field slicer is set to **Medical**, so the numbers below describe that group of **464 employees** (out of 1,470 in the dataset). Clear the slicer to see all employees.

| KPI | Value |
|---|---|
| Total Employees | 464 |
| Attrition Count | 63 |
| Active Employees | 401 |
| Attrition Rate | 14% (13.6%) |
| Average Age | 36.84 |
| Job Satisfaction | 3.1 out of 4 |

## Visuals on the dashboard

- KPI cards: total employees, active employees, attrition count, attrition rate, average age
- Job satisfaction rating (doughnut)
- Employees by gender (doughnut)
- Employees by education level (bar)
- Employees by job role (treemap)
- Employees by department (pie)
- Employees by age group (column)
- Employees by marital status (pie)
- Slicers: Gender, Education Field

## Workbook structure

| Sheet | Purpose |
|---|---|
| `Data` | Raw employee data (1,470 rows, 44 columns) stored as an Excel Table, plus helper columns for age band, attrition label and attrition flag |
| `KPI and Rating` | KPI pivot tables and the formulas behind the KPI cards and satisfaction gauge |
| `pivot_tables` | One pivot table and pivot chart for each breakdown |
| `Dashboard` | The final one-page view with slicers |

## How the KPIs are calculated

- **Total Employees** = count of Employee Number
- **Attrition Count** = sum of the attrition flag (1 = left, 0 = stayed)
- **Active Employees** = Total Employees − Attrition Count
- **Attrition Rate** = Attrition Count ÷ Total Employees
- **Job Satisfaction Rating** = average Job Satisfaction (scale of 1–4)

## Excel skills used

Pivot tables · Pivot charts · Slicers · Excel Tables · `GETPIVOTDATA` · Helper columns · Doughnut, pie, bar, column and treemap charts · Dashboard layout

## Dataset

HR employee dataset with 1,470 records and 44 fields covering demographics, job role, department, income, satisfaction scores, tenure and attrition.

## How to use

1. Download `HR_DATA_Excel.xlsx`.
2. Open it in Excel 2016 or later (treemap charts and slicers need it).
3. Go to the `Dashboard` sheet and use the slicers to filter.

## Author

**Divya** — aspiring Data Analyst, Mumbai
GitHub: [divya-singh04](https://github.com/divya-singh04)
