# DiabetesPrediction-using-various-ML_Algorithms

## Introduction

This report evaluates the performance of a diabetes prediction algorithm using various classifiers.

## Exploratory Analysis

The dataset included 7 predictor variables: Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. Key observations from exploratory analysis:

- No duplicates were found in the dataset.
- Outliers were detected and capped to minimize their impact on the analysis.
- Initially, there were no NaN (missing) values observed in the dataset. However, zeros were identified in certain features, which were treated as missing values. These zeros were replaced with NaN values, and missing data imputation techniques were applied later in the analysis.

## Classifier Scores

| Classifier                   | Score     |
|------------------------------|-----------|
| Logistic Regression          | 0.785714  |
| KNN Classifier               | 0.805195  |
| Support Vector Classifier    | 0.805195  |
| Gaussian Naive Bayes         | 0.759740  |
| Decision Trees Classifier    | 0.740260  |

## Conclusion

The KNN classifier and SVM achieved the highest accuracy of 80.51% and an AUC score of 86%. This indicates that the KNN and SVM are well-suited for predicting diabetes based on the features included in our dataset.

