# Loan Approval Prediction: A Comprehensive Machine Learning Analysis

[View the Jupyter Notebook](https://github.com/Illias-b/Loan-Approval-Notebook.git) 

## Introduction

The task of predicting loan approval is pivotal in the banking and finance sector, enabling informed decision-making. This report delineates a detailed machine learning project aimed at forecasting loan approval outcomes based on diverse applicant attributes. The process encompasses data preparation, exploratory data analysis (EDA), visualisation, outlier management, feature engineering, model training, evaluation, and comparison.

## Data Preparation and Cleaning

Initiating with data loading and preliminary inspection, we identified the data structure and pinpointed missing values. Missing values in categorical variables were substituted with the mode, and numerical variables with the median. This strategy ensures a complete dataset for more accurate model predictions.

## Exploratory Data Analysis (EDA) and Visualisation

The EDA aimed at uncovering patterns, anomalies, and correlations within the data, employing various visualisation techniques:

- **Histograms** for understanding the distribution of numerical variables.
- **Correlation heatmaps** for identifying variable relationships.
- **Count plots** for the distribution of categorical variables.

Due to the limit on the number of visualisations, we highlight the most insightful ones:


1. **Correlation Heatmap**: Provides insights into how different variables relate to each other and their impact on loan approval.
![image](https://github.com/Illias-b/Loan-Approval-Prediction/assets/33836566/bb423766-2ebf-4c53-9d78-dec87aa9076d)

2. **Count Plot for Loan Status**: Offers a clear view of the distribution of loan approval outcomes across applicants.
![image](https://github.com/Illias-b/Loan-Approval-Prediction/assets/33836566/a88b0c26-fe5c-4f42-b18d-8f2d4e1e588c)

3. **Box Plot for ApplicantIncome (Before Outlier Removal)**: Showcases the impact of outlier removal on the distribution of applicant incomes.
![newplot](https://github.com/Illias-b/Loan-Approval-Prediction/assets/33836566/35f2e9ed-4649-4ec8-949d-ae7d10118e3d)

These visualisations played a crucial role in understanding the data, guiding our preprocessing and modelling strategies.

## Outlier Removal

Outliers for `ApplicantIncome` and `CoapplicantIncome` were identified and removed using the Interquartile Range (IQR) method, essential for reducing the influence of extreme values on model performance.

## Feature Engineering

Key steps included:

- **Dropping redundant columns**: Removed columns like `Loan_ID` that do not contribute to predictive power.
- **One-hot encoding for categorical variables**: Transformed categorical variables into a format suitable for model training.

## Model Training and Evaluation

Several models were trained and evaluated:

- **Support Vector Classifier (SVC)**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

The performance of these models was assessed through accuracy and cross-validation scores, with Gradient Boosting showing promising results.

## Conclusion

In this report, we navigated through the prediction of loan approval outcomes, culminating in the selection of the Support Vector Machine (SVM) model for its effective balance of precision and efficiency. This choice underscores the model's capability to accurately predict loan approvals, offering a valuable tool for financial decision-making. Future efforts will aim to refine this model further, enhancing its predictive power for loan applicants' outcomes.
