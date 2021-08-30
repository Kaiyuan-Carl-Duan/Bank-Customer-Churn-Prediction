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

