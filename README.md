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
      
      Balanced Accuracy score: 71%
      "High Risk": precision rate - 1%, recall rate - 69%
      "Low Risk:" precision rate - 100%, recall rate - 73%%

      * Oversampling (SMOTE)
      
      Balanced Accuracy score: 61.3%
      "High Risk": precision rate - 1%, recall rate - 69%
      "Low Risk:" precision rate - 100%, recall rate - 74%%

      * Undersampling
      
      Balanced Accuracy score: 61.3%
      "High Risk": precision rate - 1%, recall rate - 74%
      "Low Risk:" precision rate - 100%, recall rate - 48%

      * Combination
      
      Balanced Accuracy score: 74.3%
      "High Risk": precision rate - 1%, recall rate - 69%
      "Low Risk:" precision rate - 100%, recall rate - 80%

      * Ensemble Learners (BalancedRandomForestClassifier)
      Balanced Accuracy score: 99.6%
      "High Risk": precision rate - 73%, recall rate - 34%
      "Low Risk:" precision rate - 100%, recall rate - 100%
      
      * Ensemble Learners (Easy Ensemble AdaBoost Classifier)
      [this model unfortunately had some error]
   
   ## Summary
   ### the majority of the model had a decent accuracy score with the exception for undersampling and oversampling. Balanced Random Forest had the highest accuracy and a high precision rate. As a data analysis, the lending company should the latter for their credit risk analysis.
