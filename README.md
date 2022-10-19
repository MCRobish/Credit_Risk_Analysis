# Credit_Risk_Analysis
## Overview of Analysis: 
The goal of this assignment was to take different techniques to train machine learning models in order to evaluate credit card risk in an unbalanced dataset. The set given had several more examples of low risk loans than high risk loans. Oversampling, undersampling and over and undersampling using SMOTEENN were used and compared. BalancedRandomForestClassifier and EasyEnsembleClassifier were also used to predict credit risk. The performance of these models are evaluated below. 

## Results: 
* **Random Oversampling** 
The model was trained and the balanced accuracy score for this data set was 83%. The precision and recall scores for high_risk and low risk loans are shown in the matrix below.The precision for high_risk loans is 0.03 and the recall is 0.82

![image](https://user-images.githubusercontent.com/105991478/196566356-1a3473fb-2585-4b20-82cd-c776e21be8f7.png)

* **SMOTE Oversampling**
The balanced accuracy score for this model was 84%. The precision and recall scores are shown below. In this model, the precision for high_risk loans is 0.04 and recall is 0.82

![image](https://user-images.githubusercontent.com/105991478/196566542-f3207a52-1583-47eb-acfb-7a4e513fe9e9.png)
* **Cluster Centroids Undersampling**
The balanced accuracy score for this model is 84%. In this model, the precision for high_risk loans is 0.04 and the recall is 0.82

![image](https://user-images.githubusercontent.com/105991478/196566834-b08a607b-c65a-46d3-a42d-1eda3391e726.png)
