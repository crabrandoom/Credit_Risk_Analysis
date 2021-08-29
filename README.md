#Credit Risk Analysis

## Overview
Machine learning was used to assess credit card risk and then the models were compared to each other . Given that credit risk is an inherently unbalanced classification problem multiple different techniques to train and evaluate models were used. The models performance was evaluated to assess whether these models should be used to predict credit risk.


## Results

The results for the RandomOverSampler:
Accuracy:0.6441747142552103

Confusion Matrix:
array([[   54,    33],
       [ 5689, 11429]], dtype=int64)

Classification Report:
                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.62      0.67      0.02      0.64      0.41        87
   low_risk       1.00      0.67      0.62      0.80      0.64      0.42     17118

avg / total       0.99      0.67      0.62      0.80      0.64      0.42     17205



The results for the SMOTE algorithm:

The results for the ClusterCentroids algorithm:

The results for the SMOTEENN algorithm:

The results for the BalancedRandomForestClassifier algorithm:

The results for the  EasyEnsembleClassifier algorithm:



## Summary

