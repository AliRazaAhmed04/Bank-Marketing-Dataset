# Bank Marketing Dataset

## Objective
The goal of this project is to predict which customers are likely to accept a personal loan offer using the Bank Marketing Dataset from the UCI Machine Learning Repository. This can help the bank target the right customers for their marketing campaigns, improving conversion rates and reducing costs.

## Problem Statement
Given customer demographic and behavioral features (such as age, job, marital status, etc.), we aim to build a classification model that accurately predicts whether a customer will accept a personal loan offer.

## Dataset
**Dataset**: https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
The dataset contains information on marketing campaigns of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (binary: yes/no).

### Target:
- `deposit`: Has the client subscribed to a term deposit? (Yes/No)

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression)

## Key Tasks
- Data Exploration and Visualization
- Preprocessing and Feature Engineering
- Classification Modeling (Logistic Regression or Decision Tree)
- Analysis of Target Customer Groups

##  Results & Insights
Accuracy: **77.88%**

     Accuracy: 77.88%
Classification Report

              precision    recall  f1-score   support

           0       0.78      0.80      0.79      1166
           1       0.78      0.75      0.76      1067

    accuracy                           0.78      2233
   macro avg       0.78      0.78      0.78      2233
weighted avg       0.78      0.78      0.78      2233

Confusion Matrix
[[938 228]
 [266 801]]
 [266 801]]
