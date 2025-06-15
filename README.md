# 📊 HR Analytics Dashboard

An interactive Tableau-built dashboard designed to uncover key HR insights using employee-level data. Explore trends in attrition, demographics, job satisfaction, age distribution, education background, and department-level attrition to support strategic workforce decisions.

- **Author**: Samiksha Kamath  
- **Project Date**: October 28, 2024

## 🛠️ Business Use Case

As an HR Analytics Consultant, I built this Tableau dashboard to help gain strategic visibility into workforce trends. By integrating employee‑level data and leveraging interactive visualizations, this enabled HR leaders to:

- **Diagnose attrition hotspots**—identifying gender imbalances, high‑turnover departments (like R&D), and mid‑career decline (ages 35–44).
- **Understand engagement gaps**—especially in HR and healthcare roles—and align retention programs for at‑risk groups.
- **Tailor talent strategies**—customizing leadership development, onboarding, and wellness initiatives based on age, education, and satisfaction insights.
- **Drive data‑informed decisions**—supporting ongoing workforce planning by spotlighting strengths (e.g., high engagement in science roles) and areas for improvement.

This dashboard empowers business stakeholders to allocate resources, refine policies, and reduce turnover costs through targeted interventions and continuous monitoring.

## ❓ What Is Attrition?

Attrition in HR refers to the gradual reduction of an organization's workforce when employees leave voluntarily (e.g., resignations, retirements) and **are not replaced**. Unlike turnover, which includes exits followed by hiring replacements, attrition leads to a net decrease in staff numbers 


## 🧭 Dashboard Features

1. **KPI Tiles**:  
   - Total Employee Count  
   - Total Attrition (sum)  
   - Active Employees  
   - Average Age  
   - Overall Attrition Rate  

2. **Attrition by Gender**: Shows absolute numbers of male vs female attrition.

3. **Department-wise Attrition**: Pie chart breaking down attrition across HR, R&D, Sales, etc.

4. **Employee Age Distribution**: Histogram with a slider-controlled bin size illustrating the age structure.

5. **Job Satisfaction Heatmap**: Tabular view of satisfaction ratings (1–4) per job role.

6. **Education-field Attrition**: Bar chart showing attrition counts by education (Life Sciences, Medical, etc.).

7. **Attrition Rate by Age and Gender**: Pie charts that display gender-specific attrition rates in age brackets (e.g. <25, 35–44, 45–54, 55+).

---

## 🔧 How It Was Created

### 1. Dashboard Design & Build (Tableau Desktop/Public)
- Imported HR dataset into Tableau.
- Created calculated fields and KPIs (e.g., Attrition Rate = `Attrition / Employee Count`).
- Designed visual elements: pie charts, histograms (with adjustable bins), heatmaps, bar charts, KPI tiles.
- Applied a consistent dark theme with contrasting orange/blue highlights.
- Exported and saved the workbook as `HR_Analytics_Dashboard.twbx`.

---

### 2. Version Control (Git & GitHub)
- Initialized a Git repo and committed:
  - `HR_Analytics_Dashboard.twbx` – packaged workbook with data
  - `hr_dashboard_screenshot.png` – high-res static preview
 ---

## 📈 Key Insights from the Dashboard

### 👥 Workforce Overview
- **1,470** total employees  
- **237** employees left (~**16.1%** attrition)  
- **Average age: 37 years**

### ⚖️ Attrition by Gender
- **150** males departed vs **87** females  
  → Male attrition is disproportionately higher relative to their population share.

### 🏢 Departmental Attrition
- **R&D** leads with 133 exits  
- **Sales** follows with 92 exits  
- **HR** shows 12 exits  
  → R&D may need targeted retention efforts.

### 🎓 Attrition by Education Field
- **Life Sciences**: 89 exits  
- **Medical**: 63 exits  
  → Suggests potential skills mismatch or competitive job market for these qualifications.

### 📊 Age & Attrition Demographics
- **Under 25**: 58 exits (~8.4%)  
- **35–44**: 68 exits (~15.6%) — highest turnover segment  
- **45–54**: 34 exits (~6.8%)  
- **55+**: 14 exits (~3.4%)  
  → Mid-career employees (35–44) are leaving at the highest rate.

### 😊 Job Satisfaction Breakdown
- **Low scores** in HR & Healthcare Representative roles  
- **High scores** among Research Scientists, Lab Technicians, Sales Executives  
  → Potential burnout or engagement issues in HR/healthcare roles; strong engagement in research and sales.

---

## 💡 Strategic Recommendations

1. **Retain R&D Talent**  
   Implement retention programs like mentorship, development paths, and recognition initiatives.

2. **Support Mid-Career Staff (35–44)**  
   Offer leadership training, mobility options, and work-life flexibility.

3. **Improve HR & Healthcare Staff Experience**  
   Introduce wellness support, workload management, and regular recognition.

4. **Align Roles for Life Sciences & Medical Graduates**  
   Redefine role expectations, career trajectory, and hiring messaging.

5. **Enhance Young Employee Onboarding (<25)**  
   Strengthen orientation, mentorship, and early engagement initiatives.

---



