# Real-Estate-Price-Prediction
This repo is a part of my portfolio of data science projects completed by me for academic, self learning, and hobby purposes.
____
***This notebook is for Kaggle competition https://www.kaggle.com/c/realestatepriceprediction.***
In this competition the task is to predict the price of flats in test.csv. Two datasets are given: train.csv (contains all features and prices of flats) and test.csv (only features).
The evaluation metric is Coefficient of determination.
Data files can be downloaded from competition's page.
My Kaggle page: https://www.kaggle.com/nikolayermolenko.
____
The main good ideas were:
* add new feature with mean square meter price by district;
* make clusterization for all objects and add feature with cluster information;
* use catboostregressor.