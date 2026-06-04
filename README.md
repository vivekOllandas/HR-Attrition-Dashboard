# 📊 HR Employee Attrition Analysis Dashboard

An end-to-end HR analytics project analyzing employee attrition 
patterns using **Excel** and **Power BI**. This project uncovers 
key insights about why employees leave and which groups are most 
at risk.

---

## 🛠 Tools & Technologies
- **Data Cleaning:** Microsoft Excel
- **Dashboard:** Power BI
- **Skills:** DAX Measures, Data Modeling, Data Visualization, 
  Power Query, Business Intelligence

---

## 📁 Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset (Kaggle)
- **Size:** 1,470 employees, 35 columns
- **Domain:** Human Resources

---

## 🧹 Excel Data Preparation
- Removed duplicates and checked for blank values
- Created `AgeGroup` column categorizing employees into 
  18-25, 26-35, 36-45, 46+
- Created `AttritionFlag` column converting Yes/No to 1/0 
  for numeric analysis
- Created `AgeSortOrder` column for correct age group sorting
- Saved cleaned file as .xlsx for Power BI connection

---

## 📊 Dashboard Visuals

### KPI Cards
![KPI Cards](screenshots/kpi_cards.png)

| Metric | Value |
|---|---|
| Attrition Rate | 16.12% |
| Total Employees | 1,470 |
| Avg Age | 36.92 |
| Avg Monthly Income | $6,502.93 |

---

### Attrition by Department
![Attrition by Department](screenshots/attrition_by_department.png)

---

### Attrition by Age Group
![Attrition by Age Group](screenshots/attrition_by_age.png)

---

### Avg Salary: Stayed vs Left
![Salary vs Attrition](screenshots/salary_vs_attrition.png)

---

### Job Satisfaction by Department
![Job Satisfaction Matrix](screenshots/job_satisfaction_matrix.png)

---

### Attrition by Gender
![Attrition by Gender](screenshots/attrition_by_gender.png)

---

## 💡 Key Insights
- Overall attrition rate is **16.12%** — 237 out of 1,470 employees left
- **R&D department** has the highest attrition with 133 employees
- **26-35 age group** has the highest attrition (116 employees) — 
  likely due to better opportunities elsewhere
- Employees who **left earned 30% less** on average than those who stayed
  (₹4,787 vs ₹6,832)
- **Males account for 63.29%** of total attrition
- **Job satisfaction score 4** has the most employees — yet attrition 
  still exists, suggesting salary is a bigger driver than satisfaction

---

## 🚀 How to Use
1. Download `HR_Attrition_Dashboard.pbix`
2. Open in **Power BI Desktop** (free download)
3. If data doesn't load, update the Excel file path in 
   Transform Data → Data Source Settings

---

## 📁 Files in This Repository
| File | Description |
|---|---|
| `HR_Attrition_Dashboard.pbix` | Power BI dashboard file |
| `HR_Attrition_Analysis.xlsx` | Cleaned Excel dataset |
| `screenshots/` | All dashboard screenshots |

---

## 👤 Author
**Vivek Ollandas**
Aspiring Data Analyst | MCA Graduate
📧 vivekollandas993@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/vivek-ollandas-5a02152b7)
