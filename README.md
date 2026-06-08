# SCT_DA_3 — Interactive Visualization Dashboard

**SkillCraft Technology | Data Analyst Internship | Task 03**

---

## 📌 Task Overview

Create an interactive report using Power BI on the HR Employee Attrition dataset. Build a dashboard that allows users to filter by Region, Age Group, or Department. The report must answer: "Why are employees leaving?"

---

## 🎯 Objectives

- Build an interactive Power BI dashboard
- Add filters for Department, Age Group, and Attrition
- Visualize attrition patterns across departments and job roles
- Answer the question: "Why are employees leaving?"

---

## 📂 Repository Structure

```
SCT_DA_3/
│
├── HR_Attrition_Dashboard.pbix          # Power BI dashboard file
├── WA_Fn-UseC_-HR-Employee-Attrition.csv  # HR dataset
└── README.md                            # Project documentation
```

---

## 🗂️ Dataset

**IBM HR Analytics Employee Attrition & Performance**

| Property | Value |
|----------|-------|
| Rows | 1,470 |
| Columns | 35 |
| Missing Values | 0 |
| Attrition Rate | 16.1% (237 employees) |
| Source | [Kaggle — IBM HR Analytics](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard creation and visualization |
| IBM HR Dataset | Source data for analysis |

---

## 📊 Dashboard Features

### Filters / Slicers
- **Department** — Human Resources, Research & Development, Sales
- **Age Group** — Under 25, 25-34, 35-44, 45-54, 55+
- **Attrition** — Yes / No

### KPI Cards
- Total Employees: **1,470**
- Total Attrition: **237**

### Visualizations
1. **Attrition by Department** — Column chart showing employee count split by attrition per department
2. **Employee Count by Age Group** — Pie chart showing age distribution
3. **Attrition by Job Role** — Column chart showing which roles have highest turnover
4. **Average Monthly Income by Job Role & Attrition** — Column chart showing income differences between employees who left vs stayed

---

## 🔍 Key Insights — Why Are Employees Leaving?

| Factor | Finding |
|--------|---------|
| Department | Sales has the highest attrition rate |
| Job Role | Sales Representatives & Lab Technicians leave the most |
| Monthly Income | Employees who left earn significantly less on average |
| Age Group | 25-34 age group has the highest number of attrition cases |
| Attrition Rate | 16.1% overall — 237 out of 1,470 employees left |

---

## ▶️ How to Open

1. Download `HR_Attrition_Dashboard.pbix`
2. Open with **Power BI Desktop** (free download from Microsoft)
3. Use the slicers on the left to filter by Department, Age Group, or Attrition
4. All charts update interactively based on your selection

---

## 📚 Key Learnings

- Power BI slicers make dashboards highly interactive and user-friendly
- Income and job role are strong predictors of employee attrition
- Visual storytelling helps communicate HR insights to non-technical stakeholders
- Age group segmentation reveals which workforce groups are most at risk

---

*SkillCraft Technology — Data Analyst Internship*
