# GoogleSheets_Cancer_issue

# 🧬 Cancer Survival Analysis – Google Sheets Case Study  
**By:** Patcharin Perngkam  
**Tools:** Google Sheets | Pivot Tables | Charts  
**Dataset:** Fictional cancer patient data (17,686 records)

---

## 📌 Project Overview

This project explores a dataset of cancer patients with the goal of identifying patterns in:
- **Survival time**
- **Cancer recurrence**
- **Demographic trends**

All analysis was done in **Google Sheets**, showcasing what's possible using pivot tables, charts, and formulas for real-world health data.

---

## 🎯 Objectives

1. Understand how survival time varies across treatments, tumor size, and cancer stage.
2. Analyze recurrence patterns across demographics and genetic markers.
3. Visualize distributions and breakdowns using pivot tables and charts.

---

## 🧼 Step 1: Data Cleaning

- Loaded the dataset (`.csv`) into Google Sheets.
- Verified correct formatting for numeric columns like `Age`, `TumorSize`, and `SurvivalMonths`.
- Removed blank or non-numeric cells for accurate charting.
- Renamed columns for clarity.

---

## 📊 Step 2: Demographic Breakdown

### ✅ Cancer Type by Gender

Used a pivot table to count patients per gender by cancer type, then visualized with a horizontal bar chart.
![Cancer Type by Gender](/Users/pp/Desktop/images/Cancer_Gender.png)

> 🔍 **Insight:** Prostate cancer appeared exclusively in male patients, while breast and skin cancer were more evenly distributed.

---

### ✅ Cancer Type by Region

Visualized the number of patients per cancer type by hospital region.

> 🔍 **Insight:** Skin and lung cancer were among the most common in every region, but slight variations existed regionally.

---

### ✅ Average Age & BMI by Cancer Type

Calculated average age and BMI using pivot tables.

> 🔍 **Insight:** Patients across all cancer types had a similar average age (around 53–54 years) and BMI (~29).

---

## 📈 Step 3: Survival Analysis

### ✅ Tumor Size vs Survival Time

Created a scatter plot with a trendline using `TumorSize` and `SurvivalMonths`.

> 📉 **Result:**  
> Equation: `y = 0.0261x + 60.2`  
> R² = 0.0  
> **Interpretation:** No strong correlation was found between tumor size and survival time.

---

### ✅ Histogram of Survival Time

Visualized how long patients lived using a histogram.

> 🔍 **Insight:** Survival time was widely spread, with some patients living beyond 100 months. There's no dominant survival period.

---

## 🔁 Step 4: Recurrence Patterns

### ✅ Recurrence by Cancer Type

> 🔍 **Insight:** Recurrence was fairly balanced across cancer types.

### ✅ Recurrence by Stage

> 🔍 **Insight:** Patients with Stage III or IV cancers had a higher recurrence count — consistent with real-world expectations.

### ✅ Recurrence by Smoking Status

> 🔍 **Insight:** Former smokers had slightly higher recurrence than current or non-smokers, though all groups were close.

### ✅ Recurrence by Genetic Marker

> 🔍 **Insight:** The KRAS genetic marker showed the highest number of recurrences, potentially signaling a biological link.

---

## ✅ Final Summary & Key Learnings

- Cancer stage has a clearer link to recurrence and survival than tumor size.
- Demographic insights (age, gender, BMI) helped reveal population patterns.
- Google Sheets can be a surprisingly powerful data tool — pivot tables, scatter plots, histograms, and formulas made it possible to extract real insights without any code.

---

## 📎 Files Included

| File | Description |
|------|-------------|
| `cancer issue.csv` | Raw dataset |
| `README.md` | This documentation |
| `/images` | Screenshots of charts and tables |

---

## 🚀 Next Steps (Optional)

- Calculate recurrence **rate (%)** per group using formulas.
- Export to **Excel, R, or Python** for advanced modeling.
- Build a dashboard in **Looker Studio** or **Tableau** for interactivity.

---
