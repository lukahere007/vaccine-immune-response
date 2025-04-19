💡 Objectives

Simulate vaccine response data over time

Explore effect of dose, comorbidities, and demographics

Conduct t-tests, ANOVA, and logistic regression

Visualize longitudinal response with R² trend lines

🛠️ Tools & Libraries

tidyverse for data manipulation

ggpubr and ggsignif for annotated boxplots

ggpmisc for polynomial trendlines with R² and equations

gghighlight for exploratory data emphasis

broom for clean model output

📊 Analysis Summary

✅ Simulated Dataset:

500 patients

Age, sex, BMI, comorbidity

Vaccine dose: Dose 1, Dose 2, Booster

Antibody titers measured at Days 0, 14, 28, 90

✅ Statistical Modeling:

One-way ANOVA comparing titers by dose (significant differences found)

Tukey’s HSD post-hoc tests

Logistic regression to predict seropositivity (titer > 50)

✅ Key Visualizations:

Boxplot: Antibody titers by dose with ANOVA + p-values

Polynomial Plot: Mean titers over time with R² and trendlines

Highlight Plot: Top 10% responders at Day 90 colored by dose

📌 Notes

Perfect adjusted R² values are expected because the polynomial models were fit on mean antibody responses at fixed timepoints.

🚀 How to Run This Project

Clone the repository:

git clone https://github.com/your-username/vaccine-immune-response.git

Open RStudio and run simulated_vaccine_analysis.Rmd

Install any missing packages interactively when prompted

👨‍💻 Author

Luka WamalwaMaster's Student, Applied Statistics & Data ScienceEmail: lukewamalwa@yahoo.com

🧠 Inspiration

This project is inspired by real-world clinical immunogenicity studies and serves as a portfolio-friendly showcase of applied biostatistics and R visualization capabilities.

✅ Future Directions

Add confidence intervals and ROC analysis

Expand to longitudinal mixed-effect modeling

Recreate analysis in Python

Deploy as a Shiny dashboard

📌 License

MIT License

 Simulated vaccine-immune-response/
├── README.md                        # Project overview and instructions
├── simulated_vaccine_analysis.Rmd  # R Markdown with full analysis
├── data/
│   └── simulated_vaccine_data.csv  # Simulated dataset
├── plots/                          # (Optional) Folder for exported plots
