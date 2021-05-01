# Credit Risk Analysis

## Overview
The following project shows several tests such as oversampling, undersampling, and a combination of ensemble techniques and logistical regression analysis to see which machine learning models performed best at determining credit-risk in the real world.

- Tools used:
-   Pandas
-   Data from Lending Club
-   Python

# Results
--------------
## Random Oversampling and Logistic Regression
Here are the results for this section:
- Accuracy Score: 0.652
- Precision: 0.99
- Recall: 0.55
- F1: 0.71

![Random Oversampling](https://user-images.githubusercontent.com/75768098/116785962-f5f5ac00-aa61-11eb-9d17-60450471529f.png)


## SMOTE Oversampling
Here are the results for this section:
- Accuracy Score: 0.646
- Precision: 0.99
- Recall: 0.69
- F1: 0.81

![Smote Oversampling](https://user-images.githubusercontent.com/75768098/116785968-f9893300-aa61-11eb-921a-9cfd3a48561d.png)

## ClusterCentroids and Undersampling
Here are the results for this section:
- Accuracy Score: 0.544
- Precision: 0.99
- Recall: 0.69
- F1: 0.56

![Undersampling](https://user-images.githubusercontent.com/75768098/116785964-f726d900-aa61-11eb-886d-a8aa8bd5890c.png)

## SMOTEENN Over/Undersampling
Here are the results for this section:
- Accuracy Score: 0.649
- Precision: 0.99
- Recall: 0.60
- F1: 0.81

![Smoteen Oversampling](https://user-images.githubusercontent.com/75768098/116785966-f8580600-aa61-11eb-824b-05beefba0521.png)

## Balanced Random Forest
Here are the results for this section:
- Accuracy Score: 0.79
- Precision: 0.99
- Recall: 0.70
- F1: 0.93

![Balanced RForest](https://user-images.githubusercontent.com/75768098/116785973-fc842380-aa61-11eb-8632-839fd09856d0.png)

## Easy Ensemble AdaBoost Classifier
Here are the results for this section:
- Accuracy Score: 0.91
- Precision: 0.99
- Recall: 0.89
- F1: 0.96

![Easy Ensemble](https://user-images.githubusercontent.com/75768098/116785971-fb52f680-aa61-11eb-867e-885709405835.png)


# Summary
--------------
Of the six machine learning models implemented, I found that four had accuracy scores that were lower than .70. Next I looked to the F1 score, and of the four that had the lowest accuracy score, two had decent F1 scores of at or more than .8 (SMOTE and SMOTEENN). What struck out to me were the F1 scores of the Balanced Random Forest and more specifically the Easy Ensemble model, which was at a staggering .96. For that reason, along with its high precision and accuracy score, I believe that the Easy Ensemble AdaBoost Classifier would be the best model to use/build off of. 
