# 📊 HR Analytics Dashboard

An interactive Power BI dashboard built to analyze employee attrition, workforce demographics, salary trends, and departmental performance across **1,480 employee records**.

---

## 🖼️ Dashboard Preview

![HR Analytics Dashboard](dashboard_preview.png)

---

## 📌 Project Overview

Employee attrition is one of the costliest challenges for any organization. This project builds a fully interactive HR Analytics Dashboard in Power BI that helps HR teams:

- Identify **which employees are most likely to leave**
- Understand **salary and age patterns** driving attrition
- Compare attrition across **departments, education fields, and job roles**
- Make **data-driven retention decisions**

---

## 📂 Dataset

| Property | Details |
|---|---|
| Source | IBM HR Analytics Dataset (Kaggle) |
| Records | 1,480 employees |
| Columns | 39 features |
| File | `HR_Analytics.csv` |

**Key columns:** Age, Department, Education, JobRole, MonthlyIncome, YearsAtCompany, Attrition, JobSatisfaction, SalarySlab

---

## 🔍 Key Business Questions Answered

1. What is the overall attrition rate in the organization?
2. Which salary slab has the highest attrition?
3. Which age group is most at risk of leaving?
4. Which departments and education fields show the highest turnover?
5. Does job satisfaction correlate with attrition?
6. How does tenure affect employee retention?

---

## 💡 Key Insights Discovered

- **19.35% overall attrition rate** — nearly 1 in 5 employees has left the organization
- **Lowest salary slab (≤ ₹5K/month)** shows the highest attrition — compensation is a major driver
- **Age group 26–35** has the highest attrition count — mid-career professionals leaving for better opportunities
- **Sales & R&D departments** have comparatively higher attrition and need targeted retention strategies
- **Life Sciences & Medical** education backgrounds contribute the most to attrition percentage
- **Job roles with lowest satisfaction** (Sales Executive, Research Scientist) also show higher turnover
- **Employees with < 2 years tenure** are most likely to leave — early engagement is critical

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard creation & interactive visualizations |
| DAX | KPI measures (Attrition Rate, Avg Monthly Income, etc.) |
| Power Query | Data cleaning and transformation |
| Excel / CSV | Source data format |

**DAX Measures Used:**
- `Total Employee Count`
- `Attrition Count`
- `Attrition Rate = DIVIDE([Attrition Count], [Total Employee Count])`
- `Average Monthly Income`

---

## 📊 Dashboard Features

- **KPI Cards** — Total Employees, Attrition Rate, Avg Monthly Income at a glance
- **Slicers / Filters** — Filter by Department, Gender, Education Field
- **Attrition by Education Field** — Pie chart breakdown
- **Attrition by Age Group** — Bar chart showing peak risk groups
- **Attrition by Salary Slab** — Clear salary-attrition relationship
- **Job Role vs Job Satisfaction** — Matrix visual
- **Attrition by Years at Company** — Tenure impact line chart
- **Attrition Rate by Department** — Departmental comparison

---

## 🗂️ Project Structure

```
HR-Analytics-Dashboard/
│
├── HR_Analytics.csv          # Source dataset (1,480 records, 39 columns)
├── HR Analytics Dashboard.pbix  # Power BI report file
├── dashboard_preview.png     # Dashboard screenshot
└── README.md                 # Project documentation
```

---

## 🚀 How to Run

1. **Download** Power BI Desktop (free) from [microsoft.com/powerbi](https://powerbi.microsoft.com/desktop/)
2. **Clone this repository:**
   ```bash
   git clone https://github.com/Shraddha567/HR-Analytics-Dashboard
   ```
3. **Open** `HR Analytics Dashboard.pbix` in Power BI Desktop
4. If prompted, re-link the data source to `HR_Analytics.csv` in your local folder
5. **Explore** the dashboard using slicers and filters

---

## 🎯 Business Impact

This dashboard enables HR teams to:
- **Monitor** employee turnover trends in real time
- **Identify** high-risk employee groups before they leave
- **Improve** retention planning with data-backed strategies
- **Support** workforce decision-making through visual analytics
- **Identified top 3 at-risk employee segments**, potentially reducing attrition planning time by **40%**

---

## 📜 License

This project is for educational and portfolio purposes only.

---

## 🙋‍♀️ About Me

**Shraddha Maheshwari** — Aspiring Data Analyst passionate about turning raw data into actionable insights.

