# Workplan

## Basic Project Description

### Team members

Leona Hasani, Leona Hoxha, Nanmanat Disayakamonpan and Nastaran Mesgari

### Main Goal or Research Question

1. Can the implementation of more sophisticated modeling methods within our dataset lead to enhanced model performance, and how can we interpret such improvements? 

2. Does it mean that if one model performs the best in one particular dataset, it would be the same for another dataset with the same method? 

3. What is ***the impact of standardization and normalization techniques*** on the performance scores of our models? 

4. How can we analyze the ***trade-off dynamics*** associated with choosing between ***the inclusion of all available features*** and employing ***feature selection techniques***? 

5. What approach can be employed to identify the optimal hyperparameters of each model? 

6. Is there a ***risk of overfitting*** within our datasets, and what ***measures*** can be taken to ***assess and mitigate*** this risk effectively?

7. How to find the ***right balance of bias and variance*** of a model?

### Data

**1.** Hotel Reservation Dataset (link: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset)

**2.** Rain in Australia Dataset (link: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

**3.** Cardiovascular Dataset (link: https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset)

### Methods

All of the three datasets that we have chosen are classification problems, where the target variable is binary. At the hotel reservation variable the target variable is whether the client has cancelled or not the hotel reservation; at the rain in Australia based on other features we want to predict the binary target variable (Yes or No) if it will rain tomorrow; in the Cardiovascular dataset the target variable is binary (Yes or No) whether the patient based on his/her other health attributes will be likely to have a heart disease in the future.

The models that we have discussed to be used in this project are:
  - Logistic Regression
  - Decision Tree
  - Random Forest and others as well.

In this project we would want to put more focus/effort into the interpretability of machine learning models,  which models to choose for a particular dataset (the same models will be applied to all of the datasets since they're all have a binary target variable, and does it mean that for example Random Forest will be performing the best at one dataset or to all of them and what are the reasons behind), how we could better interpret the accuracy scores of complex models and does it mean that the more complex a model is, the more accurate it will be in predicting, or is the other way around.
We would like to explore that how the PCA can affect the prediction modelling, specifically the differences between with/without applying PCA for each of the datasets. We would like to explore and be able to choose the bias and variance of a model (bias and variance trade-off). We want to explore the trade-off dynamics of choosing between the inclusion of all of the available features and applying feature selection techniques to the datasets. 






