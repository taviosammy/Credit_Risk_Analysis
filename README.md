# Credit_Risk_Analysis
Module 17


## Overview of the analysis: The aim of this analysis is to use different machine learning models to predict credit risk of loan application data. 
We have applied these models to assess the different accuracy results and to determine the most useful model when it comes to predicting whether someone is low 
or high risk.


Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Random Oversampling
![image](https://user-images.githubusercontent.com/99847046/183368379-65f3cf9e-1fe0-419f-b2e4-264a73bea3cc.png)
Accuracy: 0.6416 

Precision: 0.99

Recall: 0.65

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/99847046/183478053-f629a5c3-3ad9-4ec2-b4e7-56fd94939a30.png)
Accuracy: 0.6364 

Precision: 0.99 

Recall: 0.64

### Undersampling
![image](https://user-images.githubusercontent.com/99847046/183480422-75f47aff-69c0-493a-ac32-21f46cbe7d9e.png)
Accuracy: 0.53139 

Precision: 0.99  

Recall: 0.45

### Combination (Over and Under) Sampling
![image](https://user-images.githubusercontent.com/99847046/183481568-f4460041-f30f-46c7-b801-201f96a439d6.png)
Accuracy: 0.6591 

Precision: 0.99 

Recall: 0.58


### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/99847046/183483719-64f641b0-623f-4009-a115-118760d07308.png)
Accuracy: 0.7290 

Precision: 0.99 

Recall: 0.84

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/99847046/183484470-940d7816-4333-4f53-abf6-2ac69142c697.png)
Accuracy: 0.9316 

Precision: 0.99 

Recall: 0.94




# Summary: 

First thing to notice after analysing these models is that they all share the same precision score.  This means more they all are exceptional at confirming if a case is a true posivive when predicted.   They however have varying degrees of sensitivity(recall).    Between the Oversampling models and ensemble modles, ensemble proved to have higher sensitivity.  Easy Ensemble AdaBoost Classifier in particular had the highest sensitivity score of 0.94.  Having high sensitivity means more true positives vs false negative.  So using this model would limit the occurance of people with Low risk being labeled high risk.
