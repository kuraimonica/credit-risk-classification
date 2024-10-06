# credit-risk-classification
Module 20 Challenge
My code and the Credit Risk Analysis Report are in the Credit_Risk folder

Steps Taken to complete the challenge

I read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
I create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.
I split the data into training and testing datasets by using train_test_split.
Created a Logistic Regression Model with the Original Data

Using my knowledge of logistic regression I completed the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).
Saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluated the model’s performance by doing the following:
Generated a confusion matrix.
Printed the classification report.
Answered the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

I wrote a Credit Risk Analysis Report

