
# 🩺 Diabetes Analysis Project

## 📌 Overview

This project presents an in-depth statistical analysis and predictive modeling of diabetes outcomes using patient health metrics. The analysis aims to explore patterns in the dataset, identify key variables influencing diabetes risk, and build a reliable logistic regression model for prediction.

---

## 🎯 Study Objectives

1. **Explore** demographic, physical, and biochemical factors influencing diabetes.
2. **Perform** univariate, bivariate, and multivariate analysis to uncover insights.
3. **Build** a logistic regression model to predict diabetes presence.
4. **Evaluate** model assumptions and performance metrics.
5. **Visualize** the data and model outputs to support interpretation.

---

## 📊 Dataset Summary

- **Total Records**: 768
- **Features**: 9 variables including glucose, blood pressure, BMI, insulin, age, and outcome.
- **Target Variable**: `Outcome` (1 = Positive for diabetes, 0 = Negative)

---

## 🧠 Methodology

### 🔍 Data Preparation
- Assigned unique `ID` for identification.
- Converted `Outcome` to binary categories: Positive and Negative.
- Categorized variables (e.g., Age groups, Glucose levels, BMI classes).

### 📈 Exploratory Data Analysis
- Visualized distributions using bar plots, histograms, and density plots.
- Conducted univariate and bivariate analyses.
- Plotted correlation heatmaps and conducted t-tests and ANOVAs.

### 🧪 Key Findings from Statistical Tests
- **Glucose, BMI, and Age** show strong statistical relationships with diabetes outcome.
- **Higher Glucose** and **higher BMI** are significant predictors.

### 📦 Model Development: Logistic Regression
- Built using 8 predictor variables.
- Validated assumptions: No autocorrelation, low multicollinearity, no outliers.
- Evaluated model summary and odds ratios.

### 📊 Model Performance
- **AUC (ROC Curve)**: 0.8394 (Good discrimination ability)
- **Significant Predictors**: Glucose, BMI, Pregnancies, Diabetes Pedigree Function.

---

## 📌 Recommendations

1. **Public Health Campaigns**: Focus on awareness around glucose and BMI management.
2. **Early Screening**: Encourage screening for individuals with higher pregnancy counts and elevated glucose levels.
3. **Lifestyle Interventions**: Tailor dietary and physical activity programs for high-risk groups.
4. **Data-Driven Policies**: Use model insights to prioritize resource allocation in healthcare planning.

---

## 📚 Key Libraries Used

```r
library(tidyverse)
library(ggplot2)
library(pROC)
library(gtsummary)
library(ggeffects)
library(skimr)
library(performance)
library(vip)
library(ggcorrplot)
```

---

## 📁 Repository Structure

```
├── Diabetes Analysis Project.pdf
├── README.md
├── data/
│   └── diabetes.csv
├── scripts/
│   └── diabetes_analysis.R
```

---

## 👤 Author

**Enock Bereka**  
*Data Analyst | Health Informatics Enthusiast*  
📅 January 25, 2025

---

## 📝 License

This work is licensed for academic and educational use. Please credit the author if using this material.

---
