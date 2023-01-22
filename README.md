# Credit_Risk_Analysis
Module 18 Challenge - Supervised Machine Learning

## Resources
Operating Platform: Windows 11 Pro - Build 22621 [Buy Windows 11 Pro](https://www.microsoft.com/en-us/d/windows-11-pro/dg7gmgf0d8h4?rtc=1)</br>
IDE Software: [Jupyter Notebook](https://jupyter.org/) Verison 6.5.2 ()</br>
Python Kernel: 3.7.13
Completed Jupyter Notebooks: [credit_risk_resampling](credit_risk_resampling.ipynb), [credit_risk_ensemble](credit_risk_ensemble.ipynb)</br>
Resource files: [LoanStats](/Resources/LoanStats_2019Q1.csv)

## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I'll oversample the data using the ```RandomOverSampler``` and ```SMOTE``` algorithms, and undersample the data using the ```ClusterCentroids``` algorithm. Then, you’ll use a combinatorial approach of over and undersampling using the ```SMOTEENN``` algorithm. Next, you’ll compare two new machine learning models that reduce bias, ```BalancedRandomForestClassifier``` and ```EasyEnsembleClassifier```, to predict credit risk.
Below is a list of tasks which will be completed: 
* Use Resampling Models to Predict Credit Risk.
* Use the SMOTEENN Algorithm to Predict Credit Risk.
* Use Ensemble Classifiers to Predict Credit Risk.
