# traffic_accidents_prediction
Machine learning models to predict if a traffic accident will end up in casualties

## Main objective
Based on certain variables taken from a traffic accident (e.g. type of vehicle, type of road, time of the accident, main contributing factor, etc) this project aims to develop a machine learning model that can predict if such traffic accident will end up having fatal victims.

One possible application of such a model could be, for example, to quickly generate a 'main priority alert' that would be received by emergency first responders in order to activate a special, high priority response to the accident occurred. 

## The data
The data used for this project came from police records of traffic accidents occurred in the city of New York, between July 2012 and March 2023.

The data can be accessed here: https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes

## What's included
- Data cleaning and wrangling
- Data visualization
- Re-sampling techniques to deal with a very imbalanced dataset
- Training, optimization and comparison of different classification models: logistic regression, decision trees, random forests, KNN, Naive Bayes, XGBoost, LightGBM.
