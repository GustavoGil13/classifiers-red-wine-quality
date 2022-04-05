# Using various classifiers on the red wine dataset

On this notebook we attempt to test different classifiers on the popular [red wine dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?datasetId=4458&sortBy=voteCount).

The classifiers we are going to use are:
1. Logistic Regression (LR)
2. Decision Tree Classifier (DTC)
3. Random Forest Classifier (RFC)
4. Support Vector Classifier (SVC)
5. K Neighbors Classifier (KNC)
6. Gaussian NB (GNB)
7. Neural Network (NN)

We are going to use sklearn's **GridSearchCV** to exhaustively search for the best parameters to tune our models.