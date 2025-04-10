# 🏥 Elective Hip Replacement Surgeries in New York State – Data Analysis Project

---

## 📌 Project Overview

This project analyzes elective hip replacement surgeries performed in 151 hospitals across New York State. The objective is to uncover patterns in cost and length of stay (LOS), detect outlier hospitals, and identify key factors influencing patient outcomes and hospital efficiency.

Insights were derived using Power BI to support data modeling, visualization, and root cause exploration.

---

## 📊 Dataset Summary

- **Total Hospitals**: 151  
- **Total Discharges**: 26,286  
- **Average Length of Stay (LOS)**: 2.65 days  
- **Average Cost per Discharge**: $20,910  

The data covers metrics such as cost, LOS, illness severity, mortality risk, and discharge disposition.

---

## 💡 Key Insights

### 📍 Hospital Variability

- Significant **variation in cost and LOS** exists across hospitals.
- This variability is not fully explained by volume or severity alone, pointing to operational or clinical differences.

### 📍 High-Cost & Long-LOS Hospitals

- Urban hospitals, particularly those in **New York City**, consistently show higher costs and LOS.
- Contributing factors include urban cost of living, complex patient demographics, and hospital discharge challenges.

### 📍 Outliers Identified

- Some hospitals deviate substantially from state averages.
  - **High outliers** suggest potential inefficiencies or difficult cases.
  - **Low outliers** may indicate high-performing, efficient care models worth emulating.

### 📍 Volume vs. Efficiency

- Hospitals with **larger surgical programs** tend to have **slightly shorter LOS**.
- No consistent correlation with cost — scale alone does not guarantee lower expenses.

---

## 🔍 Key Questions Explored

| Question | Insight |
|---------|---------|
| Which hospitals have the highest cost and LOS? | Urban centers, especially NYC, dominate this list |
| Who are the biggest outliers? | Detected using LOS and cost deviations from average |
| Does program size matter? | Higher volume links to slightly lower LOS but not necessarily lower cost |
| What factors drive LOS and cost? | Severity, mortality risk, urban location, and skilled nursing disposition |

---

## 🧠 Root Cause Analysis

Top factors increasing LOS and cost:

| Factor | Impact |
|--------|--------|
| **Extreme illness severity** | Longer recovery, higher care intensity |
| **Major/Extreme mortality risk** | Increased monitoring and treatment needs |
| **NYC hospital location** | Higher operational costs and complexity |
| **Discharge to skilled nursing facilities** | Indicates longer post-op recovery needs |

---

## 🛠️ Tools & Techniques

- **Power BI**:
  - Data modeling and transformation
  - KPI visualizations
  - Outlier detection using visual filters
  - Root cause analysis via key influencers

