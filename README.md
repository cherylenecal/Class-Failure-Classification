# Class Failure Classification

## Introduction
This analysis aims to identify factors influencing student performance, enhancing awareness among educators and schools to improve learning outcomes.
Dataset is sourced from https://www.kaggle.com/datasets/janiobachmann/math-students.

## Methodology
Data preprocessing : Encoding and Scaling
Feature selection : F-score and Random Forest Importance, evaluated using 1-NN classifier (using 150-fold cross validation with 20 repetitions)
Model : compared between KNN, Decision Tree, Naive Bayes (compared in using all features and only 15 top important features)

## Conclusion
KNN with the top 15 features had the overall better classification performance in predicting whether or not a student fails in this dataset.
