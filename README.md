# Supervised Machine Learning Homework - Predicting Credit Risk

In this assignment, I built a machine learning model that attempts to predict whether a loan will be approved or not. 

## Background

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, I compared the Logistic Regression model and Random Forest Classifier.

## Logistic Regression

What is logistic regression in simple terms?
Logistic regression is a statistical analysis method to predict a binary outcome, such as yes or no, based on prior observations of a data set.

## Random Forest Classifier

What is random forest in simple terms?
The random forest is a classification algorithm consisting of many decisions trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree

## Results

At the end both models performed within 0.005 difference of each other, with Random Forest Classifier being just slightly higher. I believe that this indicates that there is a relationship between the independent and dependent variable within the data (as per the Logistic Regression). Since the Logisitic Rgression is easier to evaluate (and it performed so well) it would be better to use the Logistic Regression to form conclusions on this particular data set.
