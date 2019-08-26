The main goal of this project is to build a classifier to predict whether the breast cancer is malignant or benign based on the
features that are most helpful in predicting such as radius,perimeter, area, etc..
The idea is to choose the best classifier based on accuracy


The dataset used in the analysis is derived from UCI Machine Learning Repository and was created by Dr William H Wolberg 
at University of Wisconsin


We have followed the below pre-processing steps as part of this analysis:
1. Converting Categorical data into numerical data through encoding
2. Scaling

Accuracy obtained by various models are listed as below:
1.Logistic Regression: 95.8%
2.K Nearest Classifier: 95.1%
3.Support Vector Machine: 93.7%
4.Naive Bayes Classifier: 91.6%
5.Decision Tree Algorithm: 95.8%
6.Random Forest Classifier: 98.6%

From the results obtained we can conclude that the Random Forest Classifier performs the best for this problem.
