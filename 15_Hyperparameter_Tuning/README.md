# Hyperparameter Tuning Using GridSearchCV API

## Parameter vs Hyperparameter

  ### Parameter(model parameter)
  * Parameter is a configurqation variable which is internal to model and whose value can be estimated from the data
  * They are required by the model when making predictions
  * They are estimated or learned from data
  * They are often not set manually by the practitioner
  * They are often saved as part of the learned model
  * Some examples of model parameters include:
    * The weights in an artificial neural network
    * The support vectors in a support vector machine
    * The coefficients in a linear regression or logistic regression

### Hyperparameter
  * Hyperparameter are external to the model and whose values cannot be estimated based on the data
  * They are often specified by the practitioner (By testing the model with test data)
  * They are often tuned for a given predictive modeling problem.
  * They can often be set using heuristics
  * Some examples of model hyperparameters include:
    * The learning rate for training a neural network
    * The C and sigma hyperparameters for support vector machines
    * The k in k-nearest neighbors
    * No of trees (n_estimators) in RandomForest Alogirithm

## Problem Statement

* For iris flower dataset in sklearn library, we are going to find out best model and best hyper parameters using GridSearchCV or RandomizedSearchCV API for hyperparametertraining

# Reference
[What is the Difference Between a Parameter and a Hyperparameter?](https://machinelearningmastery.com/difference-between-a-parameter-and-a-hyperparameter/)
