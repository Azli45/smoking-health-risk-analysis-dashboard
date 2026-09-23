# smoking-health-risk-analysis-dashboard
# Smoking Health Risk Analysis Dashboard

An interactive Power BI dashboard that explores the relationship between smoking behavior and health risk factors such as cholesterol and hypertension, across different age groups and genders.

## Business Question

How does smoking behavior (status, duration, and daily intake) relate to health risk factors like cholesterol and hypertension across age groups and gender, and how do patient outcomes differ between healthy and at-risk profiles?

## Overview

Instead of standard tabs, the dashboard uses a custom navigation built around body organs (Heart, Human Body, Kidney, Liver, Lungs). Clicking an organ filters the report to show smoking and health risk data specific to that view. A **Healthy vs Damaged** toggle updates every visual on the page dynamically, letting users compare patient profiles across health conditions.

## Key Features

- **Organ-based navigation** — Heart, Human Body, Kidney, Liver, and Lungs views for exploring the data by body system
- **Healthy vs Damaged toggle** — dynamically updates KPIs and visuals to compare patient groups
- **KPI cards** — total patient count, average age, and average BMI, benchmarked against the overall dataset
- **Smoking status breakdown** — Never, Current, and Former smokers shown as a percentage of total patients
- **Smoking status by gender** — comparison of smoking patterns between male and female patients
- **Smoking duration vs daily intake** — years of smoking (YOS) plotted against cigarettes per day (CPD) across age groups
- **Cholesterol and hypertension risk** — High, Normal, and Low risk levels compared across six age groups (18–28 through 69+)

## Sample Insights

| View | Total Patients | Avg Age | Avg BMI |
|---|---|---|---|
| Healthy | 529 | 54.1 | 30.0 |
| Damaged | 319 | 54.9 | 29.8 |

*(Kidney view: Damaged — 174 patients, avg age 53.9, avg BMI 29.0)*

## Tools & Skills Used

- Power BI Desktop
- DAX (measures and calculated columns)
- Data modeling
- Interactive filtering and bookmarks (organ navigation, Healthy/Damaged toggle)
- Dashboard design and data storytelling

## Status

This is a personal project built for learning and portfolio purposes.

## Author

**Azli Khan**
