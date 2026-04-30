# 📊 HR Analytics Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📌 Overview

An interactive HR Analytics Dashboard built in Power BI that provides deep insights into employee attrition, salary distribution, age demographics, and job role performance. Designed to help HR teams make data-driven decisions.

---

## 📷 Dashboard Preview

![HR Analytics Dashboard](dashboard_preview.png)

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Total Attrition | 237 |
| Attrition Rate | 16.1% |
| Average Age | 36.92 |
| Average Salary | 6.50K |
| Average Years at Company | 7.01 |

---

## 🔍 Features

- **Attrition by Education** — Donut chart breaking down attrition across Life Sciences, Medical, Marketing, and Technical Degree fields
- **Attrition by Age Group** — Bar chart showing which age groups (18-25, 26-35, 36-45, 46-55, 55+) have the highest attrition
- **Attrition by Salary Slab** — Horizontal bar chart comparing attrition across salary ranges (Upto 5K, 5K-10K, 10K-15K, 15K+)
- **Attrition by Job Role** — Matrix table showing attrition count by job role and satisfaction level
- **Attrition by Gender** — Visual breakdown of male vs female attrition (140 Male, 79 Female)
- **Department Filter** — Slicer to filter data by Human Resources, Research & Development, and Sales
- **Trend Line** — Line chart showing attrition trends over time

---

## 🗂️ Dataset

- **Source:** HR Analytics Dataset
- **File:** `HR_Analytics.csv`
- **Records:** 1,470 employees
- **Fields include:** Age, Attrition, Department, Education, Job Role, Salary, Years at Company, Gender, and more

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard creation and visualization
- **DAX** — Custom measures and calculations
- **Power Query** — Data transformation and cleaning

---

## 📐 DAX Measures Used

```dax
-- Attrition Rate
Attrition Rate = SUM(HR_Analytics[Attrition Count]) / SUM(HR_Analytics[EmployeeCount])

-- Average Salary
Avg Salary = AVERAGE(HR_Analytics[MonthlyIncome])

-- Average Age
Avg Age = AVERAGE(HR_Analytics[Age])
```


## 💡 Insights Found

- **Life Sciences** has the highest attrition by education at **38%**
- The **26-35 age group** has the highest attrition with **116 employees**
- Employees earning **Upto 5K** have the highest attrition at **163**
- **Laboratory Technicians** and **Sales Executives** are the most affected job roles
- **Male attrition (140)** is significantly higher than **female attrition (79)**

---

## 👤 Author

**MustafaKhan**
- LinkedIn: [[Your LinkedIn](https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/mustafa-khannn/))

---
