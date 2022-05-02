# Credit_Risk_Analysis

## Purpose
We have been employed to apply different techniques to train and evaluate machine learning models with unbalances classes for credit risk assessment and then recommend which model should be used to predict credit risk.

## Overview

Using the credit card credit dataset from LendingCLub, we will use:

- Random Oversample algorithm

- SMOTE algorithm

- Cluster Centroid Undersampling algorithm

- SMOTEENN algorithm

- Balance Random Forest Classifer

- Easy Ensemble AdaBoost Classifer

## Results

### Random Oversample

![over](https://github.com/QQrex/Credit_Risk_Analysis/blob/main/Images/Random%20Oversample.PNG)
- Accuracy: 0.62
- Precision: 0.99
- Recall: 0.65
- F1: 0.78

### SMOTE

![smote](https://github.com/QQrex/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversample.PNG)
- Accuracy: 0.65
- Precision: 0.99
- Recall: 0.66
- F1: 0.79

### Cluster Centroid Undersampling

![under](https://github.com/QQrex/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)
- Accuracy: 0.51
- Precision: 0.99
- Recall: 0.44
- F1: 0.60

### SMOTEEN

![combine](https://github.com/QQrex/Credit_Risk_Analysis/blob/main/Images/Combine%20SMOTEENN.PNG)
- Accuracy: 0.63
- Precision: 0.99
- Recall: 0.57
- F1: 0.72

### Balance Random Forrest Classifier

![forrest](https://github.com/QQrex/Credit_Risk_Analysis/blob/main/Images/Random%20Oversample.PNG)
- Accuracy: 0.62
- Precision: 0.99
- Recall: 0.65
- F1: 0.78

### Easy Ensemble AdaBoost Classifier

![ada](https://github.com/QQrex/Credit_Risk_Analysis/blob/main/Images/Adaboost.PNG)
- Accuracy: 0.92
- Precision: 0.99
- Recall: 0.94
- F1: 0.97

## Summary

In summary, when looking at our class unbalances models (Random Oversample, SMOTE, Cluster Centroid Undersampling and SMOTEENN), we saw SMOTE algorithm performing the best with accuracy score of 0.65, precision at 0.99, recall at 0.66 and with an F1 score of 0.79. However, this model may not be the best for predicting high credit risk due to such low accuracy score.

We also looked at two ensemble classifier models (Random Forrest and Easy Ensemble AdaBoost) with Easy Ensemble AdaBoost performing well with a 0.92 accuracy, 0.99 Precision, 0.94 Recall and 0.97 F1 score. Overall, after testing all 6 models, we can say Easy Ensemble AdaBoost model performed the best due to its high accuracy score in detecting high credit risk with our given data features.
