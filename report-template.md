# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to train a logistical model to accurately predict whether a loan was high-risk or healthy.  The data used to predict the loan status included the loan size, interest rate, borrower's income, debt to income ratio, number of accounts, derogatory marks, and total debt.  First, the orignal data was split to have a set of training and testing data which was then fitted to a logistical regression model used to predict the test data.  Next, the balanced accuracy score, confusion matrix, and imbalanced classification report were generated.  Then a new set of resampled data was generated to oversample the high-risk loan data to make up for the imbalance with the amount of healthy loans.  The same procedure was done with this data which resulted in a model that predicted high-risk loans with more accuracy.  

## Results

* Machine Learning Model 1:
  * The balanced accuracy score was about 95.2% which measures how often the model was correct by calculating the ratio of the number of correct predictions to the total number of outcomes.
  * The precision score for healthy loans was 100% while high-risk loans was 85% which measures how confident we are that the model correctly made the positive predictions.
  * The recall score for healthy loans was 99% and high-risk loans was 91% which measures the number of actual healthy loans that the model correctly classified as healthy loans and the number of acutal high-risk loans that the model correctly classified as high-risk loans.



* Machine Learning Model 2:
  * The balanced accuracy score was about 99.4% which measures how often the model was correct by calculating the ratio of the number of correct predictions to the total number of outcomes.
  * The precision score for healthy loans was 100% while high-risk loans was 84% which measures how confident we are that the model correctly made the positive predictions.
  * The recall score for healthy loans was 99% and high-risk loans was 99% which measures the number of actual healthy loans that the model correctly classified as healthy loans and the number of acutal high-risk loans that the model correctly classified as high-risk loans.

## Summary

Machine Learning Model 2 seems to perform best even though the precision score for a high-risk loan is slighly lower because it excels in regards to accuracy and recall score.  In this case it is more important to identify high-risk loans ('1') correctly to protect against loaning to borrowers who are likely to default.