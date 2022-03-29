# Breast-Cancer-Prediction

I built the classification models to predict diagnoses with 4 algorithms. To avoid overfitting and find the best model, I compared those models by their __accuracy__ after applied nested CV to each.

* Decision Tree - 0.91083
* Logistic Regression - 0.97639
* KNN - 0.96324
* SVM - 0.97637

The Logistic Regression model performed the best with the best parameters: C=10, Penalty=l2. The final accuray on test data is 0.98. To provide more information on model performace, I also built the confusion matrix and plotted the ROC curve and lift curve to show it's well-performed.


The original data source is from Kaggle. Link as below:
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data
