# Pipeline in Machine Learning

This notebook implements a complete machine learning workflow, packaged entirely within a scikit-learn Pipeline, for the purpose of classification. The objective is to predict the 'Survived' outcome based on passenger features from what appears to be a version of the Titanic dataset. The use of a Pipeline ensures that all data preprocessing steps are consistently applied during both training and testing.

**Machine Learning Pipeline Steps**

1.Missing Value Imputation (trf1)

2.Categorical Encoding (trf2)

3.Feature Scaling (trf3)

4.Feature Selection (trf4)

5.Model Training (trf5)

**Results**

After fitting the entire pipeline on the training data, it was evaluated using two methods:

1.Test Set Accuracy: The accuracy of the model on the held-out test set (X_test) is 0.6257 (approximately 62.57%).

2.Cross-Validation Score: A 5-fold cross-validation (cv=5) performed on the training set yielded an average accuracy of 0.6391 (approximately 63.91%).
