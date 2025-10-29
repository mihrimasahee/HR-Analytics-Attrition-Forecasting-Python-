# HR-Analytics-Attrition-Forecasting-Python-
## 🧭 Project Overview

This project analyzes employee demographics, salary structure, education, and attrition trends to uncover key HR insights and forecast future attrition.
The dashboard and analysis help HR teams identify high-risk segments, improve retention strategies, and plan workforce capacity more effectively.

## 🧾 Dataset

* Source: Internal HRMS (not shared due to confidentiality)

* Shared Data: A sample dataset is uploaded for demonstration purposes only.

* Period Covered: 2022 – Present

## Key Fields:

- Employee ID, Department, Designation

- Joining and Assignment End Dates

- Salary (Gross)

- Gender, Education Level, Marital Status

- Employee Status (Active/Attrited)

## 📈 Analysis Steps

Performed in Power BI & Python

🔹 Data Cleaning & Preparation

- Handled missing and inconsistent fields.

- Created derived columns:

- TENURE_YEARS → Employee tenure

- SALARY_SLAB → Categorized salary into 8 ranges (e.g., Up to 20K, 21K–40K, …, 200K+)

- ATTRITION_FLAG → Marked whether an employee left the organization

🔹 Power BI Dashboard Highlights

- Attrition by Department, Gender, and Education Level

- Salary Distribution and Attrition by Salary Slab

- Tenure Analysis – when employees are most likely to leave

- KPI Cards showing:

- Current Headcount

- Attrition Rate (%)

- Average Tenure

🔹 Python Analysis

Attrition by Salary Slab
→ Identified pay bands with higher attrition risk.

Attrition by Tenure
→ Visualized when employees are most likely to leave (1–3 years spike).

Forecasting Attrition Rate (Next 12 Months)
→ Used Facebook Prophet model to predict monthly attrition rate.
→ Highlighted high-risk months using color-coded visualization.

## 🔮 Forecasting Insights (2022–Next 12 Months)

- Historical attrition rates from 2022 onward were modeled.

- Prophet model predicted upcoming 12-month attrition rates.

- High-risk months flagged in red on forecast chart for proactive HR actions.

- Seasonal patterns visible — suggesting policy or engagement timing opportunities.

## 🛠️ Tools & Technologies
Category	          Tools Used
Data Visualization	Power BI
Data Cleaning	      Power Query, Pandas
Forecasting	        Prophet
Programming	        Python
Visualization	      Matplotlib, Seaborn
Version Control	    Git & GitHub
## 📂 Repository Contents
File	Description
- HRMS_EMP_SAMPLE.xlsx	Sample dataset (demo only)
- hr_analytics_dashboard.pbix	Power BI dashboard file
- attrition_forecast.ipynb	Python notebook for analysis & forecasting
- README.md	Project documentation
