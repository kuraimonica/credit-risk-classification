# Module 12 Report Template

## Overview of the Analysis


*The purpose of this analysis is to evaluate the performance of a logistic regression machine learning model in predicting loan statuses, specifically distinguishing between healthy loans (label 0) and high-risk loans (label 1). The analysis aims to determine the model's accuracy, precision, and recall to assess its effectiveness in making reliable predictions that can inform the company's decision-making regarding loan 
approvals and risk management.

## Financial Information and Prediction Task

The dataset includes financial data, and our objective is to predict whether a particular condition is met, represented by binary labels `0` and `1`. The condition were something like loan size, interest rate, , borrower income, among other binary outcomes typical in financial datasets.

## Basic Information About the Target Variable

Before proceeding with the analysis, the value distribution of the target variable was assessed. Here’s a summary using `value_counts`:

- Class `0`: 18,765 observations
- Class `1`: 619 observations

This distribution reflects a class imbalance, with significantly more occurrences of the `0` class.

## Machine Learning Process

The analysis involved several key steps:

1. **Data Preparation**: Pre-processing of the dataset

2. **Feature Selection**: Identifying and selecting significant features that contribute to the model's predictive power.

3. **Model Training**: Testing machine learning algorithms, using `LogisticRegression`

4. **Model Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.

## Results

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
      
    * Accuracy Score: 0.99 (99% of total predictions were correct)
    * Precision:
    Class 0 (Healthy Loan): 1.00 (100% of predicted healthy loans were correct)
    Class 1 (High-Risk Loan): 0.84 (84% of predicted high-risk loans were correct)

    * Recall:
    Class 0 (Healthy Loan): 0.99 (99% of actual healthy loans were identified)
    Class 1 (High-Risk Loan): 0.94 (94% of actual high-risk loans were identified)

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

*The logistic regression model demonstrates outstanding performance in predicting healthy loans, achieving perfect precision and a high recall rate. This indicates that the model is highly reliable in identifying healthy loans without misclassifying them. For high-risk loans, the model also performs well, with a precision of 0.84 and a recall of 0.94, indicating that it effectively captures the majority of high-risk loans, though there is a slight trade-off with some false positives.
Given these results, I recommend the use of this logistic regression model for the company. The high accuracy and strong performance metrics suggest that it can be a valuable tool for making informed lending decisions and managing risk. While there is room for improvement in precision for high-risk loans, the model's overall effectiveness in distinguishing between loan statuses makes it a suitable choice for deployment in the company's loan assessment process.
