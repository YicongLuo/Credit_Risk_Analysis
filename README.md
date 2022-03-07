# Credit_Risk_Analysis
## Purpose
Jill asks me use 6 models to predict credit risk, and find which one is best.
## result
Naive Random Oversampling:
1. balanced accuracy is 67% 
2. the precision is 1% 
3. the recall is 74%
![1](1.png)

SMOTE Oversampling:
1. balanced accuracy is 66% 
2. the precision is 1% 
3. the recall is 63%
![2](2.png)

Undersampling:
1. balanced accuracy is 66% 
2. the precision is 1% 
3. the recall is 69%
![3](3.png)

Combination (Over and Under) Sampling:
1. balanced accuracy is 54% 
2. the precision is 1% 
3. the recall is 81%
![4](4.png)

Balanced Random Forest Classifier:
1. balanced accuracy is  76% 
2. the precision is 3% 
3. the recall is 66%
![5](5.png)

Easy Ensemble AdaBoost Classifier:
1. balanced accuracy is 92% 
2. the precision is 9% 
3. the recall is 89%
![6](6.png)

## Summary
The first four models are dtermine which model is best at predicting which loans are the highest risk. The last twoare classfy the loan are high risk or loan risk. I think the Easy Ensemble AdaBoost Classifier is the best, becasue it have the highest balanced accuracy score is 91%.

