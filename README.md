# 🏢 Employee Attrition Prediction using Machine Learning

This project aims to predict employee attrition (whether an employee is likely to leave the company) using machine learning models. By analyzing historical HR data, the system helps organizations identify key factors driving attrition and proactively address them.

## 📌 Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## 📝 Introduction
Employee attrition, or turnover, is a critical issue faced by organizations. Predicting which employees are at risk of leaving can enable HR departments to take preventative measures. This project builds a machine learning pipeline to predict attrition based on employee data.

## 📂 Dataset
The dataset used is the **IBM HR Analytics Employee Attrition & Performance** dataset, containing various features about employees, such as:
- Age
- Job Role
- Job Satisfaction
- Monthly Income
- OverTime
- Distance from Home
- Years at Company
- And many more…

You can download the dataset from [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset) or directly include it in the `/data` folder.

## 🏷️ Features
- Categorical and numerical feature preprocessing
- Encoding categorical variables
- Handling class imbalance
- Feature scaling
- Exploratory Data Analysis (EDA)
- Feature importance visualization

## 🤖 Machine Learning Models
The following models were trained and evaluated:
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier
  
Hyperparameter tuning was performed using **GridSearchCV** or **RandomizedSearchCV**.

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix


