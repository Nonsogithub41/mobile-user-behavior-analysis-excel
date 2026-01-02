# mobile-user-behavior-analysis-excel
Mobile user behavior analysis in Excel — KPIs, PivotTables, and dashboards to explain engagement, data usage, and battery drain patterns.
# Mobile User Behavior Analysis (Excel)

This project analyzes mobile user behavior to understand **engagement patterns** and how engagement relates to **app usage time, screen time, data usage, and battery drain**.  
All analysis was done in **Microsoft Excel** using **helper KPI columns, PivotTables, and PivotCharts**.

---

## Business Question
What separates **highly engaged users** from **low-engagement users**, and what “cost” comes with that engagement (time, data, battery)?

---

## Dataset
- 700 simulated users
- Columns include: app usage time, screen time, data usage, battery drain, apps installed, age, engagement level, etc.

> Note: The dataset is simulated to reflect diverse mobile usage scenarios.

---

## Tools Used
- Microsoft Excel (Tables, formulas, PivotTables, PivotCharts)

---

## KPI Helper Columns (Formulas)
**Active user (≥60 min/day)**
```excel
=IF([@[App Usage Time (min/day)]]>=60,"Yes","No")

