# Credit_Risk_Analysis

## Overview of Project

### Purpose
For this project, we want the ability to predict the credit risk for people who apply. To do this we use many libraries to make use of machine learning models to make the predictions. 

## Results
### Balanced Random Forest Classifier
- Accuracy: 78%
- Precision: 99%
- Recall Scores: 91%

![Balanced Random Forest Classifier]( https://github.com/Robeliom15/Credit_Risk_Analysis/blob/main/images/Balanced%20Random%20Forest%20Classifier.png?raw=true)

### Combination (Over and Under) Sampling
- Accuracy: 54%
- Precision: 99%
- Recall Scores: 57%

![Combination (Over and Under) Sampling]( https://github.com/Robeliom15/Credit_Risk_Analysis/blob/main/images/Combination%20(Over%20and%20Under)%20Sampling.png?raw=true)

### Easy Ensemble AdaBoost Classifier
- Accuracy: 92%
- Precision: 99%
- Recall Scores: 94%

![Easy Ensemble AdaBoost Classifier]( https://github.com/Robeliom15/Credit_Risk_Analysis/blob/main/images/Easy%20Ensemble%20AdaBoost%20Classifier.png?raw=true)

### Naive Random Oversampling
- Accuracy: 64%
- Precision: 99%
- Recall Scores: 58%

![Naive Random Oversampling]( https://github.com/Robeliom15/Credit_Risk_Analysis/blob/main/images/Naive%20Random%20Oversampling.png?raw=true)

### SMOTE Oversampling
- Accuracy: 65%
- Precision: 99%
- Recall Scores: 68%

![SMOTE Oversampling]( https://github.com/Robeliom15/Credit_Risk_Analysis/blob/main/images/SMOTE%20Oversampling.png?raw=true)

### Undersampling
- Accuracy: 65%
- Precision: 99%
- Recall Scores: 40%

![Undersampling]( https://github.com/Robeliom15/Credit_Risk_Analysis/blob/main/images/Undersampling.png?raw=true)

## Summary

When looking for a good machine learning model to use we need a good balance of accuracy, precision, and recall scores. The only model that fits this is the easy ensemble adaBoost classifier since all three are around 90%. The other models do not have a good enough balance to be used for what we are looking for.