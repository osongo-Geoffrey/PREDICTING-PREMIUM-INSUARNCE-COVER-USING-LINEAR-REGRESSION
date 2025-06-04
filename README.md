# PREDICTING-PREMIUM-INSUARNCE-COVER-USING-LINEAR-REGRESSION
Linear Regression model for predicting insurance charges using demographic and behavioral data.
# 📊 Predicting Insurance Premium Charges Using Linear Regression

## Overview
In the competitive insurance industry, accurately predicting premium charges is essential for maintaining profitability while offering fair rates. This project implements a **Linear Regression** model to estimate individual **insurance premium charges** based on customer attributes, including:

- Age  
- Sex  
- Body Mass Index (BMI)  
- Number of children  
- Smoking status  
- Region

The goal is to create a transparent and interpretable model that supports fair, data-driven pricing decisions and offers insights into the factors driving insurance costs.

---

## 💡 Objectives

- Build a robust regression model to predict insurance charges.
- Identify the most significant predictors of premium pricing.
- Quantify the impact of lifestyle choices (e.g., smoking) on insurance costs.
- Explore regional and demographic variations in premium charges.
- Support decision-making for risk assessment and strategic pricing.

---

## 🛠️ Tools & Technologies

- **Python**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Model building & evaluation  
- **Google Colab** – Interactive coding environment

---

## 📈 Workflow

1. **Data Loading & Exploration**  
   - Understand data structure and distribution  
   - Check for missing values and duplicates 

2. **Exploratory Data Analysis (EDA)**  
   - Visualize relationships between features and insurance charges  
   - Detect multicollinearity and correlations

3. **Data Preprocessing**
   - Encode categorical variables  
   - Normalize/standardize features (if needed)  
   - Split dataset into training and testing sets

4. **Model Building**  
   - Train a Linear Regression model  
   - Interpret model coefficients  
   - Evaluate model performance (R², MAE, MSE)

5. **Insights & Interpretation**  
   - Analyze how each feature contributes to predictions  
   - Highlight key factors influencing insurance costs

---

## 🔍 Key Findings

- **Smoking status** is the strongest predictor of high premium charges.
- **Age** and **BMI** have a positive correlation with insurance costs.
- **Regional differences** exist but are less influential than health-related factors.
- **Children** and **sex** have minimal impact on pricing in this dataset.

---

## 📊 Results

| Metric       | Value |
|--------------|-------|
| R² Score     | * 0.7736* |
| Mean Squared Error (MSE)  | *38740781.4033* |



