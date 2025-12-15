# Bike Share Demand Analysis (Washington, D.C.)

**Author:** Mitchell Fields  
**Focus:** Data Analysis, Statistical Modeling, PCA, Regression  

## 🧭 Overview
This project analyzes bike-sharing rental data from Washington, D.C. (2011–2012) to understand how weather conditions, seasonality, and temporal factors influence daily bike rental demand. The analysis applies statistical methods and predictive modeling to identify the strongest drivers of usage, with relevance to transportation planning, environmental impact, and public health decision-making.

## 🔍 Analysis Performed
- Cleaned and prepared bike-sharing and weather data for analysis using R.
- Conducted exploratory data analysis (EDA) to understand trends and distributions.
- Applied Principal Component Analysis (PCA) to identify variables contributing most to demand variability.
- Performed hypothesis testing (t-tests and Wilcoxon rank-sum tests) to evaluate seasonal differences in rental volume.
- Built and compared multiple linear regression models to quantify the impact of temperature, month, and season on daily rental counts.

## 🧪 Tools & Technologies
- **R:** data manipulation, PCA, statistical testing, regression modeling  
- **Statistical Methods:** PCA, correlation analysis, hypothesis testing, linear regression  
- **Data Visualization:** ggplot2  
- **Git / GitHub:** version control and project documentation  

## 📈 Key Findings
- Temperature showed a strong positive relationship with daily bike rental demand (Spearman ρ ≈ 0.62).
- Statistically significant differences in rental volume were observed between several seasonal groupings, particularly summer vs. spring.
- PCA indicated that temperature, season, and month explain a substantial portion of variance in bike rental usage.
- Regression models confirmed temperature as the strongest predictor of daily rental counts, with seasonal and temporal factors providing additional explanatory power.

## 📂 Files
- `fields_final_project_finalcut.html` — Rendered analysis and visualizations.  
- `README.md` — Project documentation.

## 🚀 Next Steps
- Incorporate additional weather severity indicators (e.g., snowfall, extreme precipitation).
- Compare weekday vs. weekend rental behavior.
- Extend the analysis to hourly-level data for finer-grained demand forecasting.
You can view the interactive report here:  
👉 [Open the Final Project](https://htmlpreview.github.io/?https://github.com/FieldsM03/DSA587_final_project/blob/main/fields_final_project_finalcut.html)
