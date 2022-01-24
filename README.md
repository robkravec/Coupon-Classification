# Portfolio Project

## Predicting Coupon Acceptance Using Machine Learning Algorithms

### Rob Kravec

## Abstract

In this project, several machine learning algorithms were applied to a binary
classification task to maximize prediction accuracy. The data set was generated 
by a survey on Amazon Mechanical Turk, which offered “Turkers” with high ratings
targeted "20% off" coupons to local businesses. The goal was to predict 
whether a given coupon had been accepted based on information about the user, 
context, and coupon. To this end, the data set was explored and cleaned.
Following feature 
engineering, four machine learning algorithms, Support Vector Machines (SVM), 
Random Forest, AdaBoost, and XGBoost were implemented. For each algorithm, 
hyperparameters were tuned using cross-validation, and model reliance was 
calculated for models with optimal hyperparameters, providing a measure of 
variable importance. Weighted averages of predicted 
probabilities between tuned models were also considered to increase predictive
accuracy. An ensemble formed by a simple average of XGBoost and SVM predictions
achieved the best observed test accuracy of 77.92%.
