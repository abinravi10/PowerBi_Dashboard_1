# 🩺 Sweet Spot: Diabetes Analytics Dashboard

An interactive healthcare analytics dashboard built using **Power BI** to analyze patient demographics, clinical vitals, and diabetes risk factors based on 768 patient records.

## 📊 Dashboard Preview
![Dashboard Preview](dashboard_preview.png)

---

## 🛠️ Project Workflow & Steps

1. **Data Cleaning & Preparation**: Imported `sugar_power_bi.xlsx` (`diabetes new` table) and formatted columns for analysis.
2. **DAX & Calculated Columns**:
   - Created **`BMI Category`** to segment patients (Normal, Overweight, Obese, Underweight).
   - Created **`Age Category`** to group patient age brackets.
   - Created **`Risk Of Getting Diabetes`** to classify risk tiers (High, Medium, Low).
3. **Custom Measures**:
   - **`DiabetesRisk %`**: Normalizes and scales the pedigree function for the gauge chart.
4. **Visualizations Included**:
   - **KPI Cards**: Total Patients (768), Average Glucose, BMI, Skin Thickness, and Pregnancies.
   - **Area Chart**: Tracked glucose trends across age groups.
   - **Donut & Pie Charts**: Risk distribution and BMI category breakdowns.
   - **Bar Chart**: Average blood pressure by age.
   - **Gauge Chart**: Scaled diabetes risk target indicator.
   - **Matrix Table**: Detailed cross-tabulation of age and BMI categories.

---

## 📂 Files in this Repository
- `dibetes_bi_project.pbix`: The complete Power BI source file.
- `sugar_power_bi.xlsx`: The source dataset used for this project.
- `dashboard_preview.png`: Visual snapshot of the final report.
