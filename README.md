# Loan Approval Prediction Analysis Report

[View the Jupyter Notebook](https://github.com/Illias-b/Loan-Approval-Notebook.git) 

## Introduction

This report unfolds the analytical journey undertaken to forecast loan approval outcomes. Leveraging a dataset encompassing diverse applicant attributes, the process entailed comprehensive data preparation, exploratory data analysis (EDA), and the adept application of machine learning models. This analysis showcases the ability to extract meaningful insights from complex data and to develop predictive models that can guide decision-making in financial contexts.

## Exploratory Data Analysis (EDA) Insights

### Income Distributions

The exploration began with the analysis of income distributions for applicants and coapplicants. The findings revealed a skew towards lower income levels, indicating a substantial segment of the applicant pool might be financially vulnerable. This insight is critical for tailoring loan products to meet the needs of this demographic effectively.

### Loan Amount Insights

Further analysis on the distribution of loan amounts illustrated a right-skewed pattern, with a majority of applications for smaller loan amounts, though a notable minority sought larger loans. This variance in loan amounts underscores the diversity in financial needs and aspirations among applicants.

![image](https://github.com/Illias-b/Loan-Approval-Prediction/assets/33836566/d1364a0d-0d3a-42d2-bf1a-be5ddd268472)

### Correlation Insights

A correlation heatmap was constructed to identify relationships between key numerical variables. A moderate correlation between applicant income and loan amount was discerned, highlighting income as a factor in loan sizing but not the sole determinant. This nuanced view suggests that loan approval processes need to account for a broader range of factors beyond income alone.

![image](https://github.com/Illias-b/Loan-Approval-Prediction/assets/33836566/84448d4c-3e3f-46a4-80da-c3bbb701d0b6)

### Addressing Outliers

The identification and treatment of outliers in income and loan amount data were crucial steps in ensuring the integrity and reliability of the predictive models. Outliers, representing extreme cases, were meticulously addressed to prevent potential skewing of analysis results.

## Data Cleaning and Preprocessing

Following EDA, a rigorous data cleaning process was implemented to address missing values and outliers, ensuring a robust dataset for modelling. Furthermore, categorical variables were encoded to enable their inclusion in the predictive analysis, facilitating a more comprehensive evaluation of factors influencing loan approval.

## Model Selection and Evaluation

The selection of machine learning models was informed by the characteristics of the dataset and insights from EDA. A variety of classifiers, including SVM, Decision Trees, Random Forest, and Gradient Boosting, were evaluated for their capacity to navigate the dataset's complexities. This evaluative process underscores the analytical rigor applied in selecting the optimal model for predicting loan approvals.

## Conclusion

The exploratory data analysis provided profound insights into the financial backgrounds and needs of loan applicants, guiding the subsequent steps of data cleaning, preprocessing, and model selection. By addressing outliers and leveraging the relationships between variables, the dataset was meticulously prepared for effective model training. This analysis demonstrates a structured approach to predictive modelling, offering valuable insights for financial institutions in making informed loan approval decisions. Through careful examination and model selection, this work contributes to the broader discourse on the application of machine learning in finance, illustrating the potential to enhance decision-making processes with data-driven insights.
