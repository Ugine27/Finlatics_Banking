# Bank Term Deposit Subscription Prediction

## Overview

Developed a machine learning model to predict whether a customer is likely to subscribe to a bank term deposit based on demographic, financial, and marketing campaign data. The project aims to help banks optimize telemarketing efforts by identifying high-potential customers, reducing operational costs, and improving campaign efficiency.

## Features

## Data Preprocessing

- Handled missing values and duplicate records.
- Cleaned and prepared customer banking data for analysis.
- Performed feature encoding for machine learning models.

## Exploratory Data Analysis (EDA)

- Analyzed customer demographics including age, job, marital status, and education.
- Examined financial indicators such as account balance, housing loans, and personal loans.
- Investigated campaign-related features including contact type, call duration, and previous campaign outcomes.
- Identified key patterns influencing term deposit subscriptions.

## Machine Learning Pipeline

- Built an end-to-end prediction workflow from data preprocessing to model evaluation.
- Trained and compared multiple classification models.
- Predicted customer likelihood of subscribing to a term deposit.

## Model Evaluation

- Evaluated models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- Addressed class imbalance by focusing on metrics beyond accuracy.
- Compared model performance to identify the most effective classifier.

## Data Visualization

- Visualized customer demographics and financial characteristics.
- Analyzed campaign performance using statistical plots and charts.
- Generated insights to support marketing decision-making.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results

On the current dataset, the professional pipeline selected Logistic Regression as the best model by F1 score.

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.8592 | 0.4457 | 0.8300 | 0.5800 | 0.9211 |
| Decision Tree | 0.8816 | 0.4944 | 0.5005 | 0.4974 | 0.7163 |
| Random Forest | 0.9033 | 0.7081 | 0.2956 | 0.4171 | 0.9264 |

## Resume Description

Built an end-to-end machine learning pipeline to predict term deposit subscription from banking marketing campaign data. Performed EDA, feature preprocessing, classification modeling, and model evaluation using Python, pandas, seaborn, and scikit-learn.

## Applications

- Banking Analytics
- Customer Segmentation
- Marketing Campaign Optimization
- Subscription Prediction
- Financial Data Analysis

## Impact

Developed a predictive analytics solution that enables banks to identify customers with a higher likelihood of subscribing to term deposits, improving campaign targeting efficiency and supporting data-driven marketing strategies.
