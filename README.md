#Credit Risk Analysis

## Overview
Machine learning was used to assess credit card risk and then the models were compared to each other . Given that credit risk is an inherently unbalanced classification problem multiple different techniques to train and evaluate models were used. The models performance was evaluated to assess whether these models should be used to predict credit risk.


## Results

The results for the RandomOverSampler:

![ROS.PNG](https://github.com/crabrandoom/Credit_Risk_Analysis/blob/main/ROS.PNG)

The results for the SMOTE algorithm:

![SMOTE.PNG](https://github.com/crabrandoom/Credit_Risk_Analysis/blob/main/SMOTE.PNG)

The results for the ClusterCentroids algorithm:

![CLUSTER.PNG](https://github.com/crabrandoom/Credit_Risk_Analysis/blob/main/CLUSTER.PNG)

The results for the SMOTEENN algorithm:

![SMOTEENN.PNG](https://github.com/crabrandoom/Credit_Risk_Analysis/blob/main/UNDER.PNG)

The results for the BalancedRandomForestClassifier algorithm:

![BRFC.PNG](https://github.com/crabrandoom/Credit_Risk_Analysis/blob/main/BRFC.PNG)

The results for the  EasyEnsembleClassifier algorithm:

![BOOST.PNG](https://github.com/crabrandoom/Credit_Risk_Analysis/blob/main/BOOST.PNG)

## Summary

The best model used in this analysis was the EasyEnsemble classified with and Accuracy of 0.942 and an F1 score of .14 for the high risk category. In the case of credit risk detection it is better to include more false positives in order to make sure all that all true positives are flagged. The sensitivity, or recall, of this model was the best out of all of the models with a score of .91 for high risk cases. This ensures that while some may be falsely flagged as high risk, the overall majority of the actual high risks cases are flagged.

