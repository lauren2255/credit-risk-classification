## A model that can identify the creditworthiness of borrowers was created using financial data in order to predict healthy loans or loans that have a high risk of defaulting. The following specifications were followed in creatin gthe model.

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
A model that can identify the creditworthiness of borrowers was created using financial data to predict healthy loans or loans that have a high risk of defaulting. The following specifications were followed in creating the model.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
## Model Creation Process

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.
1. **Read the Data**: Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Split the data into training and testing datasets by using train_test_split.
2. **Data Preparation**:
   - Create the labels set (y) from the “loan_status” column, where 0 indicates a healthy loan and 1 indicates a high risk of defaulting.
   - Create the features (X) DataFrame from the remaining columns.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
3. **Data Splitting**: Split the data into training and testing datasets by using train_test_split.

Fit a logistic regression model by using the training data (X_train and y_train).
4. **Logistic Regression Model**:
   - Fit a logistic regression model using the training data (X_train and y_train).
   - Save the predictions for the testing data labels using the testing feature data (X_test) and the fitted model.

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
5. **Model Evaluation**:
   - Generate a confusion matrix.
   - Print the classification report.

6. **Analysis**: Answer the question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Evaluate the model’s performance by doing the following:
## Results

Generate a confusion matrix.
- **Logistic Regression Model**:
  - Accuracy: 
  - Precision for healthy loans (class 0): 
  - Recall for healthy loans: 
  - Precision for high-risk loans (class 1): 
  - Recall for high-risk loans: 

Print the classification report.
## Summary

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

## This code was authored by Lauren Ables-Torres and edX Bootcamps, LLC.
