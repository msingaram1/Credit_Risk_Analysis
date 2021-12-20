# Credit_Risk_Analysis

### Analysis Overview
Several machine learning models were analyzed to evaluate credit risk. 
Specifically, we

 1. Oversampled the data using the RandomOverSampler and SMOTE algorithms.
 2. Undersampled the data using the ClusterCentroids algorithm
 3. Used a Combinatorial Approach of over and undersampling using the SMOTEENN algorithm
 4. Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and     EasyEnsembleClassifier

After evaluating all these options we will make a recommendation on which method to use. 

### Results
# RandomOverSampler Model
![image](https://github.com/msingaram1/Credit_Risk_Analysis/blob/main/resources/oversampling.PNG)
Accuracy is at 62.9%, Precision is at 99%, and recall is at 68%.
# SMOTE model  
![image](https://github.com/msingaram1/Credit_Risk_Analysis/blob/main/resources/smote.PNG)
Accuracy is at 62.7%, Precision is at 99%, and recall is at 63%.
# Undersampling
![image](https://github.com/msingaram1/Credit_Risk_Analysis/blob/main/resources/under.PNG)
Accuracy is at 52.9%, Precision is at 99%, and recall is at 45%.
# Combination
![image](https://github.com/msingaram1/Credit_Risk_Analysis/blob/main/resources/combo.PNG)
Accuracy is at 61.9%, Precision is at 99%, and recall is at 54%.
# Balanced Random Forest Classifier
![image](https://github.com/msingaram1/Credit_Risk_Analysis/blob/main/resources/random forest.PNG)
Accuracy is at 78.7%, Precision is at 99%, and recall is at 91%.
# Easy Ensemble AdaBoost Classifier
 ![image](https://github.com/msingaram1/Credit_Risk_Analysis/blob/main/resources/easy ensemble.PNG)
 Accuracy is at 93.2%, Precision is at 99%, and recall is at 91%.


### Summary
All models don't show great precision in determining if credit risk is high. However, the ensemble models brought a lot more improvement specially on the sensitivity of the high risk credits. The EasyEnsembleClassifier model shows a recall of 92% indiciating that it detects most high risk credit. This also implies there is low precision. Compared to the other models, I think the easy ensemble provides the best balance of precision and recall scores. 
