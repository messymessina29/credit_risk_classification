# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to look at low and high risk loans and using machine learning algorithms to predict if a person should be classified as either high risk or healthy bsaed on other features. The goal is to predict 'loan_status' using other variables like loan size, debt to income, loan size, and number of accounts to classify a loan as healthy or unhealthy. I conducted a Logistic Regression to analyze how well the model can predict any input as a 0(healthy) or 1 (high-risk).


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model:
    * Accuracy: The overall accuracy score of the model was a 99%. This is largely due to the fact that the model earned a perfect score in precision and recall for predicting healthy loans.
    * Precision: The model earned a perfect score in precision for healthy loans(100%) while an 87% for predicting high risk loans. This is probably due to the fact that the majority of the data in the loan_status column was 0(healthy).
    * Recall: The model earned a perfect score in recall for healthy loans mostly due to the fact of the heavy bias in the data set towards healthy loans. The model was 89% correct for predicting high risk loans.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

In conclusion, the model performed the best at predicting healthy loans as compared to predicting high-risk loans. Overall the accuracy score of the model was 99% meaning that I would recommend this model for use by the company. However, I would also consider the fact that the model's data contained about 97% healthy loans and only 3% high-risk loans indicating that there might be an inherent bias in the model. I would recommend pulling a data set with more high-risk classified loans to get a better prediction. Since it is more important for a company to identify the higher-risk loans, I would recommend finding a model that will better predict those high-risk candidates since an 88% accuracy score still indicates you are incorrectly giving out a loan to someone who doesn't deserve it 1/10 times.
