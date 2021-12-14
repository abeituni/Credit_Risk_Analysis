# Credit_Risk_Analysis

## Overview
For this challenge, we used 6 different Machine Learning algorithms to predict credit risk based on consumer data. With these algorithms, we assessed which model would work best for predicting risk.


## Results
-Naive Random Oversampling:
  - Balanced Accuracy: 64.9%
  - Precision: 99%
  - Recall: 68%
 ![Naive Random Oversampling](https://github.com/abeituni/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.png)
 
-SMOTE Oversampling:
  - Balanced Accuracy: 64.4%
  - Precision: 99%
  - Recall: 66%
![SMOTE Oversampling](https://github.com/abeituni/Credit_Risk_Analysis/blob/main/Images/SmoteOversampling.png)

-Undersampling:
  - Balanced Accuracy: 64.4%
  - Precision: 99%
  - Recall: 45%
![Undersampling](https://github.com/abeituni/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)

-Combo Sampling:
  - Balanced Accuracy: 52.9%
  - Precision: 99%
  - Recall: 45%
![Combo Sampling](https://github.com/abeituni/Credit_Risk_Analysis/blob/main/Images/CombinationSampling.png)

-Balanced Random Forest Classifier:
  - Balanced Accuracy: 81.6%
  - Precision: 99%
  - Recall: 91%
![BRFC](https://github.com/abeituni/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.png)

-Easy Ensemble AdaBoost Classifier:
  - Balanced Accuracy: 68.9%
  - Precision: 100%
  - Recall: 100%
![EEABC](https://github.com/abeituni/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleAdaBoostClassifier.png)

## Summary
Based off our results, Balanced Random Forest Classifier & Easy Ensemble AdaBoost Classifier had the highest percentage of balanced accuracy. Precision was high with all 6 algorithms; all being 99 or 100%. Balanced Random Forest Classifier had the highest recall percentage with 91%. Based off the results of the data, it seems like the Balanced Random Forest Classifier would be the best Machine Learning algorithm to use for an analysis like this one. 
