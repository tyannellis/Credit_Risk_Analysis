# Credit_Risk_Analysis

## Overview of Analysis 
The purpose of this analysis is to see which resampling method and machine learning model is the most accurate for determining credit risk. This is done using oversampling, undersampling, and a combinational approach all with the logistic regression model. Next we use two different machine learning models that reduce bias. 

## Results 

### Naive Random Over Sampling 
![image](https://user-images.githubusercontent.com/100391913/199609648-559edc2b-edc5-48f6-88ed-471d81c0c6c0.png)
![image](https://user-images.githubusercontent.com/100391913/199607834-8a6846d6-6cd1-4f26-a821-5c76396fabb1.png)

* Balanced Accuracy Score: 64%
* Precision Score: 99%
* Recall Score: 61%

### SMOTE Resampling 
![image](https://user-images.githubusercontent.com/100391913/199609588-e81e8a3e-f302-4971-b39a-0795f2cba8b8.png)
![image](https://user-images.githubusercontent.com/100391913/199608752-9823ea97-4add-44cd-a32c-8f0d78ea79d1.png)

* Balanced Accuracy Score: 63%
* Precision Score: 99%
* Recall Score: 61%

### Undersampling 
![image](https://user-images.githubusercontent.com/100391913/199609511-91dc2a17-b78f-49eb-8219-9290fd8a4eaa.png)
![image](https://user-images.githubusercontent.com/100391913/199609095-687a6b18-97e2-40e5-a11b-0aa7c7c7bb8d.png)

* Balanced Accuracy Score: 51%
* Precision Score: 99%
* Recall Score: 41%

### Combination
![image](https://user-images.githubusercontent.com/100391913/199609410-44e7f5e2-0c43-4ff3-8e41-c6a3ea6a23bc.png)
![image](https://user-images.githubusercontent.com/100391913/199609334-272a3451-7dba-42c0-a488-bb365a5d58db.png)

* Balanced Accuracy Score:69%
* Precision Score: 99%
* Recall Score: 58%

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/100391913/199610344-d457e903-2cd9-4cbd-a54f-f5930c2491c1.png)
![image](https://user-images.githubusercontent.com/100391913/199610389-84645426-06b2-4675-886c-6952f86ccb73.png)

* Balanced Accuracy Score:74%
* Precision Score: 99%
* Recall Score: 89%

### Easy Ensemble AdaBoost Classifier 

* Balanced Accuracy Score:92%
* Precision Score: 99%
* Recall Score: 93%
