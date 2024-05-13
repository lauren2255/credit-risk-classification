# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

The purpose of the analysis was to develop machine learning models in order to predict loan status based on various factors. The model took data about loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt in order to predict the loan status, i.e. if the loan is healthy (`loan_status = 0`), or if the loan is at a high risk of defaulting (`loan_status = 1`).

The stages of the machine learning process were as follows:
1. Reading in the data
2. Splitting the data into labels and features
3. Splitting the data into test and train datasets
4. Creating a logistic regression model
5. Fitting the model with training data
6. Creating predictions using the testing feature data
7. Generating a confusion matrix and classification report with the predictions to evaluate the model

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Precision for healthy loans: 1.00
    * Recall for healthy loans: 1.00
    * F1-score for healthy loans: 1.00
    * Precisions for high-risk loans: 0.87
    * Recall for high-risk loans: 0.89
    * F1-score for high-risk loans: 0.88
    * Accuracy: 0.99


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Based on the evaluation of the model, Model 1 (Logistic Regression) demonstrates high performance in predicting healthy loans and high-risk loans. It achieves high precision and recall scores for both labels along with a very high accuracy score, however it demonstrates better performance for healthy loans compared to high-risk. In these circumstances, one is likely trying to predict the high-risk loans since they are evaluating creditworthiness of borrowers, so there may be cause to seek a model with higher precision and recall scores for loans at a high risk of defaulting. Despite this, it performs well and can be used for predicting this information.
