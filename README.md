# Using various classifiers on the red wine dataset

On this notebook we attempted to test different classifiers on the popular [red wine dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?datasetId=4458&sortBy=voteCount).

The classifiers we used were:
1. Logistic Regression (LR)
2. Decision Tree Classifier (DTC)
3. Random Forest Classifier (RFC)
4. Support Vector Classifier (SVC)
5. K Neighbors Classifier (KNC)
6. Gaussian NB (GNB)
7. Neural Network (NN)

We also used sklearn's **GridSearchCV** to exhaustively search for the best parameters to tune the classifiers.
Based on our testing, we found out that the **Random Forest Classifier** has the best performance compared to the others tested models.