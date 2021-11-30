# Credit Risk Analysis
## Overview
The purpose of this analysis is to employ different techniques to train and evaluate models using a credit card dataset to see whether they should be used to predict credit risk. We want to see how all the factors in our resource dataset (loan_stats.csv) help predict whether a person is of low or high risk status. We create a model to predict the credit risk of an individual, and then we train the model for better accuracy and evaluate whether it can be used to predict credit risk of people. 

## Results
### Naive Random Oversampling
* Balanced accuracy score is **62.4%** overall, the precision is at **99%** and the recall is **65%**.
[image]

### SMOTE Oversampling
* Balanced accuracy score is **65.1%** overall, the precision is at **99%** and the recall is **66%**.
[image]

### Undersampling
* Balanced accuracy score is **51.0%** overall, the precision is at **99%** and the recall is **44%**.
[image]

### Combination (Over and Under) Sampling
* Balanced accuracy score is **61.6%** overall, the precision is at **99%** and the recall is **54%**.
[image]

### Balanced Random Forest Classifier
* Balanced accuracy score is **78.7%** overall, the precision is at **99%** and the recall is **91%**.
[image]

## Summary
