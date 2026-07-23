# 💧 Pump It Up: Water Pump Status Prediction

## Overview

This repository contains a **Machine Learning** project that predicts the operational status of water pumps in Tanzania using the **Pump It Up: Data Mining the Water Table** (https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) dataset.

The project follows a complete end-to-end machine learning pipeline, including **exploratory data analysis**, **data preprocessing**, **feature engineering**, **feature selection**, **class imbalance handling**, **model training**, **hyperparameter tuning**, and **performance evaluation**.

The objective is to accurately classify each water pump into its corresponding operational status, supporting data-driven decision-making for water infrastructure maintenance.

## 🚀 Features

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing value imputation
- Categorical feature encoding
- Feature selection based on feature importance
- Handling class imbalance with **SMOTE**
- Hyperparameter optimization using **Grid Search**
- Comparison of multiple machine learning models
- Prediction generation for unseen data

## 🤖 Models

Several classification algorithms are trained and evaluated, including:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost

## 📊 Evaluation

Model performance is assessed using standard classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Matplotlib
- Plotly
- SciPy
- Jupyter Notebook

## 📂 Dataset

The project uses the **Pump It Up: Data Mining the Water Table** dataset, which contains information about thousands of water pumps in Tanzania. The goal is to predict whether each pump is:

- Functional
- Functional but needs repair
- Non-functional
