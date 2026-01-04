# 🩺 Diabetes Prediction Challenge  
*Kaggle Playground Series – Season 5, Episode 12*

**Competition link:**  
👉 https://www.kaggle.com/competitions/playground-series-s5e12/overview

## 📘 Overview

The **Diabetes Prediction Challenge** is part of Kaggle’s *Playground Series (Season 5, Episode 12)* and focuses on building **machine learning models to predict diabetes diagnosis** based on health, lifestyle, and demographic indicators.

The dataset is **synthetic but realistic**, designed to resemble real-world medical and behavioral data. The competition is ideal for practicing **exploratory data analysis (EDA)**, **feature engineering**, and **classification modeling** on large-scale tabular data.

## 🎯 Objective

Given a set of health-related features, the goal is to **predict whether an individual has been diagnosed with diabetes**.

- **Problem type:** Binary classification  
- **Target variable:** `diagnosed_diabetes`  
- **Evaluation metric:** ROC AUC (as defined by the competition)

## 📊 Dataset Highlights

- Demographics (age, gender, ethnicity, education, income)
- Lifestyle factors (diet, physical activity, sleep, screen time, alcohol, smoking)
- Clinical measurements (BMI, blood pressure, cholesterol, triglycerides)
- Medical history indicators (family history, hypertension, cardiovascular history)
- Large-scale dataset (~700k rows)

## 🛠 Suggested Approach

1. Perform EDA to understand feature distributions and correlations  
2. Handle categorical variables and scale numerical features  
3. Train baseline models (Logistic Regression, Random Forest)  
4. Experiment with gradient boosting models (LightGBM, XGBoost, CatBoost)  
5. Tune hyperparameters and validate using cross-validation  
6. Generate predictions and submit to Kaggle

## 🚀 Goal of This Project

This repository aims to:
- Explore the dataset in depth  
- Build reproducible ML pipelines  
- Compare multiple models and feature engineering strategies  
- Achieve strong leaderboard performance while maintaining clean, explainable code  

Happy experimenting and good luck on the leaderboard! 🏆