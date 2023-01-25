# Credit_Risk_Analysis

## Overview of the analysis
A lending company wanted to keep up with the technolagy and leverage machine learning in their process for credit risk prediction. We used multiple machine learning models to help make the appropriate prediction for the company. The different models were as follow: 

    * Oversampling: RandomOverSampler and SMOTE algorithms
    * Undersampling: ClusterCentroids algorithm
    * Combinatorial approach of over- and undersampling: SMOTEENN algorithm
    * Predict credit risk: BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results:
### Despite some minor error with the EasyEnsembleClassifier, we were able to successfully model each approach.
      * Oversampling or RandomOverSampler 
      
    Balanced Accuracy score: 65.3%
    "High Risk": precision rate - 1%, recall rate - 75%
    "Low Risk:" precision rate - 100%, recall rate - 62%

      * Oversampling (SMOTE)
      
    Balanced Accuracy score: 65.3%
    "High Risk": precision rate - 1%, recall rate - 75%
    "Low Risk:" precision rate - 100%, recall rate - 62%

      * Undersampling
      
    Balanced Accuracy score: 65.3%
    "High Risk": precision rate - 1%, recall rate - 75%
    "Low Risk:" precision rate - 100%, recall rate - 62%

      * Combination
      
    Balanced Accuracy score: 65.3%
    "High Risk": precision rate - 1%, recall rate - 75%
    "Low Risk:" precision rate - 100%, recall rate - 62%

      * Ensemble Learners (BalancedRandomForestClassifier)
      * Ensemble Learners (Easy Ensemble AdaBoost Classifier)
      
