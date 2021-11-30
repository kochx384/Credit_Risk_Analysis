# Credit Risk Analysis
## Overview
The purpose of this analysis is to employ different techniques to train and evaluate models using a credit card dataset to see whether they should be used to predict credit risk. We want to see how all the factors in our resource dataset (loan_stats.csv) help predict whether a person is of low or high risk status. We create a model to predict the credit risk of an individual, and then we train the model for better accuracy and evaluate whether it can be used to predict credit risk of people. 

## Results
### Naive Random Oversampling
* Balanced accuracy score is **62.4%**, the precision is at **99%** and the recall is **65%**.
<img src="https://github.com/kochx384/Credit_Risk_Analysis/blob/main/images/Naive_Random_Oversampling_results.PNG">

### SMOTE Oversampling
* Balanced accuracy score is **65.1%**, the precision is at **99%** and the recall is **66%**.
<img src="https://github.com/kochx384/Credit_Risk_Analysis/blob/main/images/SMOTE_Oversampling_results.PNG">

### Undersampling
* Balanced accuracy score is **51.0%**, the precision is at **99%** and the recall is **44%**.
<img src="https://github.com/kochx384/Credit_Risk_Analysis/blob/main/images/undersampling_results.PNG">

### Combination (Over and Under) Sampling
* Balanced accuracy score is **61.6%**, the precision is at **99%** and the recall is **54%**.
<img src="https://github.com/kochx384/Credit_Risk_Analysis/blob/main/images/combination_results.PNG">

### Balanced Random Forest Classifier
* Balanced accuracy score is **78.7%**, the precision is at **99%** and the recall is **91%**.
<img src="https://github.com/kochx384/Credit_Risk_Analysis/blob/main/images/Balanced_Random_Forest_Classifier_results.PNG">

## Summary
The first four models that were tried were from the Resampling techniques: undersampling, oversampling and a combination of both. The fifth model used the ensemble classifier for prediction. For the first four models, the accuracy scores were not as high compared to the fifth model Balanced Random Forest Classifier. Also, the recall scores are lower in the first four models compared to the fifth model Balanced Random Forest Classifier. Due to the accuracy, precision and recall scores all being higher in the Balanced Random Forest Classifier model, I recommened this model over the first four models. The Random Forest Classifier is the best for predicting credit risk because of the high accuracy score and the good balance of precision and recall scores.
