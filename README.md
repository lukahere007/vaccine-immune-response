# 📊 Exploring Vaccine-Induced Immune Response  
**A Simulated Clinical Dataset | R Portfolio Project**

📄 [Click here to view the full report on RPubs](https://rpubs.com/lukahere007/vaccine-response)

---

## 📁 Project Structure

---

## 💡 Objectives
- Simulate vaccine response data over time
- Explore effect of dose, comorbidities, and demographics
- Conduct t-tests, ANOVA, and logistic regression
- Visualize longitudinal response with R² trend lines

---

## 🛠️ Tools & Libraries
- `tidyverse` for data manipulation
- `ggpubr` and `ggsignif` for annotated boxplots
- `ggpmisc` for polynomial trendlines with R² and equations
- `gghighlight` for exploratory emphasis
- `broom` for tidy model output

---

## 📊 Analysis Summary

### ✅ Simulated Dataset:
- 500 patients
- Features: age, sex, BMI, comorbidity
- Vaccine doses: Dose 1, Dose 2, Booster
- Timepoints: Day 0, 14, 28, and 90 post-vaccination

### ✅ Statistical Modeling:
- One-way ANOVA comparing titers by dose
- Tukey’s HSD post-hoc comparisons
- Logistic regression to predict seropositivity (titer > 50)

### ✅ Visualizations:
- **Boxplot** with ANOVA + p-values
- **Polynomial trend plot** of mean titers over time (with equations and adjusted R²)
- **Highlight plot** of top 10% responders at Day 90

---

## 📌 Notes
> Perfect adjusted R² values are expected because the polynomial models were fit on mean antibody responses at fixed timepoints. This is intentional and interpretable.

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/lukahere007/vaccine-immune-response.git
