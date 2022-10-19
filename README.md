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
The balanced accuracy score for this model is 84%. In this model, the precision for high_risk loans is 0.03 and the recall is 0.83

![image](https://user-images.githubusercontent.com/105991478/196567155-42ac55ab-fc82-481e-b794-dcae083b5d2d.png)


* **SMOTEENN Over and Undersampling**
The balanced accuracy score for this model is 84%. The imbalanced classification report is shown below. The precision for high_risk loans is 0.03 and the recall is 0.83

![image](https://user-images.githubusercontent.com/105991478/196567419-5bc114d4-43d3-4d0e-a774-48837c4ec0fc.png)

* **Balanced Random Forest Classifier** The balanced accuracy score for this model is 76%. The precision for high_risk loans is 0.03 and the recall is 0.63

![image](https://user-images.githubusercontent.com/105991478/196567813-78945561-e627-426f-a5cc-fb0282415c47.png)

* **EasyEnsemble Classifier**
The balanced accuracy score for this model is 93% and the precision is 0.09 for high risk loans. The recall is 0.92 

![image](https://user-images.githubusercontent.com/105991478/196567925-7c0379b5-893a-4353-ba62-4445de3681b9.png)

