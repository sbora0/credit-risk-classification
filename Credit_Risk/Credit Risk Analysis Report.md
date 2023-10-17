## Credit Risk Analysis Report

## Overview of the Analysis

* The purpose of this analysis is to build a machine learning model to identify the creditworthiness of loan borrowers.
* The dataset of past lending transactions was provided by a lending company which includes loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt,
  and a machine learning model is built in this activity to determine if the loans are healthy(low-risk) or high-risk based on the loan status.
* The stages of the machine learning process used in this activity includes:
  * Reading the data from a csv file.
  * Creating the features and target lables.
  * Splitting the data into training and testing dataset.
  * Creating the Logestic Regression model.
  * Making predictions for testing dataset.
  * Evaluating the model's performance.

## Results

* Description of Accuracy, Precision, and Recall scores for Logestic Regression model.
  * The model performs well in predicting both the healthy and high-risk loans with a balanced accuracy of 94%.
  * This model has a precision score of 100% for the healthy loans and 87% for the high-risk loans.
  * This model has a recall score of 100% for the healthy loans and 89% for the high-risk loans.

## Summary

The logestic Regression model performed well in classifying healthy vs high-risk loans with a balanced accuracy of 94%, but looking at the precision and recall scores for both healthy and high-risk loans it can be easily determined that the model is not the best fit for high-risk loans.
The lower precision and recall score of high-risk loans is because of the imbalanced data with only 3% of the target values(1) for high-risk loans.
As it is more important for a lending company to identify the high-risk loan, this model requires a balanced data with fewer false predictions for testing data and making correct predictions with high precision and recall scores for high-risk loans. 

