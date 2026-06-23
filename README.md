## Simple Linear Regression – Marketing ROI Analysis

## Overview

This project applies **Simple Linear Regression (Ordinary Least Squares - OLS)** to a marketing dataset to analyze the relationship between advertising channels and sales performance.

The goal is to identify which advertising channel has the strongest impact on Sales and use this insight to support data-driven marketing budget decisions.

---

## Problem Statement

Marketing teams invest in multiple advertising channels (TV, Radio, Social Media), but it is often unclear which channel contributes most to sales performance.

This project answers the question:

> Which advertising channel has the strongest relationship with Sales?

---

## Dataset Description

The dataset contains marketing performance data with the following variables:

* **TV**: Advertising spend/value for TV campaigns

* **Radio**: Advertising spend/value for Radio campaigns

* **Social_Media**: Advertising spend/value for Social Media campaigns

* **Sales**: Revenue generated from marketing efforts

* Total observations: 4,572 rows

* Features: 4 numeric variables

* No categorical variables

---

## Objectives

* Clean and prepare the dataset for analysis
* Perform Exploratory Data Analysis (EDA)
* Identify the most relevant predictor of Sales
* Build a Simple Linear Regression model using OLS
* Evaluate model assumptions
* Interpret results in a business context
* Provide a marketing budget recommendation

---

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels

---

## Methodology

1. **Data Cleaning**

   * Handled missing values
   * Verified data types
   * Checked for duplicates

2. **Exploratory Data Analysis (EDA)**

   * Summary statistics
   * Correlation analysis
   * Data visualization (scatter plots)

3. **Variable Selection**

   * Identified strongest predictor using correlation analysis

4. **Model Building**

   * Simple Linear Regression using OLS (Statsmodels)

5. **Model Evaluation**

   * R-squared
   * p-values
   * Residual diagnostics
   * Linearity, normality, homoscedasticity checks

6. **Interpretation**

   * Statistical interpretation of coefficients
   * Business insights

---

## Key Findings

* TV advertising shows the strongest relationship with Sales
* Radio shows a moderate relationship
* Social Media shows the weakest relationship
* The regression model explains a very high proportion of variation in Sales

---

## Recommendation

Based on the analysis:

* Prioritize **TV advertising** for maximum impact on Sales
* Maintain **Radio advertising** as a secondary channel
* Optimize or reassess **Social Media advertising** effectiveness

---

## Model Summary

* Model Type: Simple Linear Regression (OLS)
* Dependent Variable: Sales
* Independent Variable: TV
* R²: ~0.999 (very strong explanatory power)

---

## Limitations

* The model uses only one predictor variable
* No time-based or cost-based analysis included
* Causal relationships cannot be confirmed
* Dataset lacks contextual business variables (e.g., ROI, campaign duration)

---

## Future Improvements

* Extend to Multiple Linear Regression
* Include marketing cost data for ROI analysis
* Explore non-linear relationships
* Add time-series analysis if temporal data becomes available

---

## How to Run the Project

```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

Run the Jupyter Notebook:

```bash
jupyter notebook regression_analysis.ipynb
```

---

## Author

Ibrahim Yisau Oluwatobiloba

Built as part of the 3MTT Data Science/AI learning program.(Airtel NextGEN)
