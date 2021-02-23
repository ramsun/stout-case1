# stout-case1
The models used in this website were created with Python's library Scikit Learn.  The tables and pictures used in the website are screenshots saved from the Jupyter Notebook used to create the predictive models.  You can access the notebook found in this repo more easily via the NBViewer link below:
https://nbviewer.jupyter.org/github/ramsun/stout-case1/blob/main/case1.ipynb

## Website Screenshot
### Landing Page
![Landing](/readme_assets/landing.png "Landing Page Screenshot")

## Purpose:
Being able to actuarately classify a transaction as fraudulent is extremely important for any bank.  This process can be difficult for massive organizations, but with the help of machine learning, the process can be made easier.  This repo showcases the use of the Logistic Regression and Random Forest classification algorithms for classifying a transaction as fraudulent or not. 

## How?:
The models themeselves were built with the package Scikit learn.  Before building the models, I made sure to follow a rigourous 5 step exploratory data analysis process, which included dropping unnecessary columns, checking for nans, creating a correlation matrix, checking for skew, and checking the balance within the labels.  Also, before running the models, feature engineering was performed on the payment type column.

The models themeselves were assessed with confusion matrices, and the Random Forest algorithm was further assessed with an ROC curve.  Since the labels were imbalanced, I made sure to perform as k-fold cross validation to ensure the train-test splits were not imbalanced.  A k value was 2 was used in this exploration, which greatly improved the model's accuracy for both the Logistic Regression and Random Forest algorithms.

## Data Sources:
https://www.kaggle.com/ntnu-testimon/paysim1

## Tools used:
Python 
Scikit Learn
Pandas
Matplotlib 
JavaScript  
HTML  
CSS  
Bootstrap  