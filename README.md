# Credit Risk Classification
A model that can identify the creditworthiness of borrowers was created using financial data to predict healthy loans or loans that have a high risk of defaulting. The following specifications were followed in creating the model.

## Model Creation Process

1. **Read the Data**: Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

2. **Data Preparation**:
   - Create the labels set (y) from the “loan_status” column, where 0 indicates a healthy loan and 1 indicates a high risk of defaulting.
   - Create the features (X) DataFrame from the remaining columns.

3. **Data Splitting**: Split the data into training and testing datasets by using train_test_split.

4. **Logistic Regression Model**:
   - Fit a logistic regression model using the training data (X_train and y_train).
   - Save the predictions for the testing data labels using the testing feature data (X_test) and the fitted model.

5. **Model Evaluation**:
   - Generate a confusion matrix.
   - Print the classification report.
   
6. **Analysis**: Answer the question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Results

- **Logistic Regression Model**:
  - Accuracy: 
  - Precision for healthy loans (class 0): 
  - Recall for healthy loans: 
  - Precision for high-risk loans (class 1): 
  - Recall for high-risk loans: 

## Summary

The logistic regression model's performance is essential for predicting both healthy and high-risk loans accurately. Further analysis is needed to determine the model's suitability for real-world deployment. 

This code was authored by Lauren Ables-Torres and edX Bootcamps, LLC.
