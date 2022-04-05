# Bank-Customer-Churn-Prediction

This is a supervised learning project to develop algorithms for telecommunications service vendors to predict customer churn probability
based on labeled data. 

## Steps:
- Preprocessed data set by data cleaning, categorical feature transformation and standardization.
- Trained supervised learning models including Logistic Regression, Random Forest and K-Nearest Neighbors, and applied
regularization with optimal parameters to overcome overfitting.
- Evaluated model performance of classification via 5-fold cross-validation technique and analyzed feature importance to
identify top factors that influenced the results.

## Results of Model Evaluation - Confusion Matrix:

| Models            | Precision  |   Recall  | Accuracy  |
|-------------------|------------| -------   |-----------|
|Logistic Regression|  0.60      | 0.19      | 0.81      |
|Random Forest      |  0.80      | 0.43      | 0.86      |
|KNN                |  0.70      | 0.36      | 0.84      |
|Naive Bayes        |  0.58      | 0.36      | 0.81      |

## Feature Importanc of Random Forest

|Features          |Feature Importance|
|------------------|------------------|
|Age               |0.2428            |
|Estimated Salary  |0.1453            |
|Credit Score      |0.1446            |
|Balance           |0.1427            |
|Number of Products|0.1296            |
|Tenure            |0.0817            |
|is Active Member  |0.0383            |
|Geography Germany |0.0205            |
|Gender            |0.0182            |
|Has Credit Card   |0.0178            |
