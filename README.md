# SME-Churn-Prediction

## 💼 Overview

Welcome! This repository showcases my work from the BCG Data Science Job Simulation on Forage, where I tackled a real-world business challenge: predicting churn for a major utility provider serving small and medium enterprises (SMEs).

The project was designed to simulate the actual workflow of a BCG data scientist — from raw data exploration to executive-level insights.

## 🎯 Objectives

-Understand and analyze churn drivers with a focus on price sensitivity.
-Build a predictive model to identify customers at high churn risk.
-Provide actionable recommendations to support strategic retention efforts.

## 🗂️ Data

-`clean_data_after_eda.csv`: Pre-cleaned dataset used for feature engineering.
-`data_for_predictions.csv`: Final dataset containing engineered features for modeling.

## ⚙️ Methodology

### 🔎 Exploratory Data Analysis (EDA)
-Assessed customer consumption patterns, contract details, and churn trends.
-Identified price volatility as a key churn driver.

### ✨ Feature Engineering
-Created features like contract tenure, consumption ratios, forecast error, price spread, and price change metrics.
-Engineered a key feature: December–January price difference, highlighting seasonal price sensitivity.

### 🤖 Predictive Modeling
-Trained a Random Forest classifier (scikit-learn) to predict churn risk.
-Achieved a robust ROC-AUC score of ~0.85, indicating strong model performance.
-Analyzed feature importance to understand business drivers.

## 💡 Key Insights
-💰 Price sensitivity is the top churn driver, especially sudden price increases.
-🤝 Customers with longer tenure and more stable consumption patterns are less likely to churn.
-🎯 The predictive model allows targeted retention efforts, optimizing business impact.

##🚀 Business Impact
-Support for proactive retention campaigns (loyalty discounts, targeted offers).
-Potential to significantly reduce churn and protect SME revenue.
-Enhances customer trust and lifetime value through informed, data-driven engagement.

##🙌 Acknowledgements
Thanks to BCG and Forage for designing this immersive virtual simulation and providing an excellent opportunity to apply data science skills to a real-world business problem.
