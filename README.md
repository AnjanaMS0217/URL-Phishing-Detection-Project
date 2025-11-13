# 🛡️ Phishing URL Detection using Ensemble Machine Learning Models
## 📘 Overview

This project detects phishing websites based on their URL features using multiple ensemble machine learning models.

It uses the PhiUSIIL Phishing URL Dataset and compares the performance of models such as:
  
  -Random Forest
  
  -AdaBoost
  
  -Gradient Boosting
  
  -XGBoost
  
  -LightGBM

The model learns to identify suspicious URL patterns and classify them as either Legitimate (0) or Phishing (1).



## 📂 Dataset

Dataset Name: PhiUSIIL Phishing URL Dataset

Format: CSV (inside archive.zip)

Source: [Academic research dataset containing extracted URL-level features.](https://www.kaggle.com/datasets/ndarvind/phiusiil-phishing-url-dataset)


## ⚙️ Project Workflow

Import libraries and load the dataset

Data exploration (EDA) — check distributions, correlations, missing values

Data preprocessing — drop irrelevant columns, clean data

Model training — use 5 ensemble models for comparison

Evaluation — accuracy, precision, recall, F1, ROC-AUC metrics

Visualization — metric comparison, confusion matrix, ROC curve

## 🧠 Models Used

Model	Description :

Random Forest	- Bagging-based ensemble for stability and accuracy

AdaBoost -	Boosting method that focuses on difficult samples

Gradient Boosting -	Sequential learners reducing bias

XGBoost	- Optimized gradient boosting with regularization

LightGBM	- Fast, high-performance gradient boosting framework
