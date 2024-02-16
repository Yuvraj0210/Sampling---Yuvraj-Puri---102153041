# ASSIGNMENT-1
# Sampling
## Problem: Balancing the imbalanced
The Credit card dataset is imbalanced with only 9 entries of Class:'1' and
over  700 entries of class:'0'
This means even if we predict the answer as '0' or 'not fraud',our accuracy would be well 
above **95!**

To Solve this issue, we can use the either **Over Sampling** or **Under Sampling** 
Since the count of class:'1' is too low,i choose to perform  **Oversampling**
using the **SMOTE: Synthetic Minority Oversampling Technique**

## Sampling:
I have used 5 techniques for sampling which are:
1. **Simple Random Sampling**
2. **Systematic Sampling**
3. **Cluster Sampling**
4. **Stratified Sampling**
5. **Bootstrap**

## Classification Models:
This is a binary classification task for which i have used 5 classification models:-
1. **Support Vector Machine**
2. **Logistic regression**
3. **Random Forest**
4. **Naive Bayes**
5. **Decision Tree**

This is my Final result after applying all models on all types of sampling

| Classifier | Simple Random | Systematic | Cluster | Stratified | Bootstrap |
|---|---|---|---|---|---|
| SVM          | 94.270833 | 88.020833 | 89.873418 | 89.583333 | 91.145833 |
| Logistic Regression | 94.270833 | 89.062500 | 89.873418 | 92.187500 | 93.750000 |
| Decision Tree   | 93.229167 | 89.583333 | 89.873418 | 95.833333 | 93.229167 |
| Random Forest  | 97.395833 | 95.833333 | 94.303797 | 98.437500 | 98.437500 |
| Naive Bayes  | 85.937500 | 76.041667 | 92.405063 | 83.333333 | 82.812500 |


## The maximum value 98.4375 is found in  Random Forest Model and  Stratified  Sampling





