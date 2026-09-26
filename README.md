# Employee Attrition Analysis

SQL & Power BI analysis of employee attrition, using the IBM HR Analytics dataset (1,470 employees), to identify key drivers of attrition and provide data-backed retention recommendations.

## 📁 Dataset

- **Source:** [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) (Kaggle)
- **Size:** 1,470 employee records
- **Key fields:** Age, Department, JobRole, MonthlyIncome, YearsAtCompany, OverTime, JobSatisfaction, Attrition

## 🛠️ Tools Used

- **SQL (SQLite)** — data exploration and aggregation
- **Power BI** — interactive dashboard and visualization

## 🔍 Process

1. Imported the raw CSV into a SQLite database
2. Wrote SQL queries to calculate attrition rate across multiple dimensions (department, tenure, income, overtime, job satisfaction)
3. Built an interactive Power BI dashboard with KPI cards, slicers, and category-level breakdowns
4. Translated findings into a written insights summary with business recommendations

## 📊 Key Insights

| # | Finding | Key Number |
|---|---------|------------|
| 1 | Overall attrition rate | **16.12%** (237 of 1,470 employees) |
| 2 | Overtime is the strongest driver | **30.53%** attrition (overtime) vs **10.44%** (no overtime) — ~3x higher |
| 3 | Early-tenure risk | **29.82%** attrition in first 2 years vs **8.13%** for 10+ years |
| 4 | Income-linked attrition | **28.61%** (lowest income band) vs **5.64%** (highest income band) |
| 5 | Satisfaction-linked attrition | **22.84%** (low satisfaction) vs **11.33%** (high satisfaction) |
| 6 | Department risk | Sales **20.63%**, HR **19.05%**, R&D **13.84%** |
| 7 | Role & age risk | Sales Representatives **39.76%**; employees under 25 **35.77%** |

## 💡 Business Recommendations

- Prioritize workload/overtime management, especially in the Sales team
- Strengthen onboarding and early-career engagement programs (0–2 year mark)
- Review compensation
