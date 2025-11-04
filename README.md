# CMS Hospital Quality Analysis

**Exploratory Data Analysis and Predictive Modeling of Hospital Quality Ratings**  
**Author:** Sumith Kumar Kurapati  
**University of New Haven**  

---

## Tools and Technologies
| Category | Tools |
|-----------|--------|
| Programming Language | R |
| Libraries | tidyverse, dplyr, ggplot2, janitor, readr, broom, caret, tidymodels |
| Techniques | Data Wrangling, Exploratory Data Analysis, Correlation Analysis, Regression Modeling |
| Visualization | ggplot2, base R plotting |
| Documentation | RMarkdown |

---

## Project Overview
This academic project analyzes hospital performance data from the **Centers for Medicare & Medicaid Services (CMS)** to identify key factors influencing hospital quality ratings.  
Using R programming, the study performs data cleaning, exploratory data analysis (EDA), and regression modeling to determine how different domains—such as mortality, readmission, and patient experience—impact the overall hospital rating.

The results can help healthcare organizations focus on the most critical performance indicators to improve patient care and overall quality outcomes.

---

## Objectives
- Clean and preprocess the CMS hospital dataset.  
- Conduct exploratory data analysis (EDA) to identify patterns and trends.  
- Visualize hospital performance metrics and overall ratings.  
- Build predictive models for hospital quality ratings.  
- Interpret results and provide actionable insights for improvement.

---

## Methodology

1. **Data Preparation**
   - Converted ordinal text categories to numeric codes.
   - Handled missing values through removal or median imputation.
   - Standardized variable formats for modeling.

2. **Exploratory Data Analysis (EDA)**
   - Visualized rating distributions using histograms and boxplots.
   - Assessed relationships between overall ratings and individual quality domains.

3. **Modeling**
   - Built a multiple linear regression model using six performance domains as predictors.
   - Evaluated model fit using R-squared, F-statistic, and coefficient significance.

---


## Results Summary

- Most hospitals received ratings of 3 or 4 stars, indicating average to above-average performance.
- The regression model achieved an R² of 0.717, explaining approximately 72% of the variance in overall ratings.
- Mortality, readmission, and patient experience comparisons had the strongest predictive power.
- Timeliness and effectiveness of care showed weaker or statistically insignificant effects.

---

## Key Insights

- Hospitals with better mortality, readmission, and patient experience scores tend to receive higher overall ratings.
- Patient experience emerged as a strong predictor, even when clinical outcomes were average.
- Enhancing patient-centered care and reducing readmissions may significantly improve hospital ratings.
- Non-clinical factors like patient experience can act as proxies for overall quality in some cases.

---
## Contact

**Sumith Kumar Kurapati**  
Email: sumithkumar222@gmail.com  
LinkedIn: linkedin.com/in/ sumithkurapati






