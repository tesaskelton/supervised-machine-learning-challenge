# supervised-machine-learning-challenge


## Background from Bootcampspot
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

## Python File Name
Credit Risk Evaluator.ipynb


## Methods Used
Supervised Machine Learning

## Machine Learning Models
*Logistic Regression
*Random Forest Classifier

## Tasks Performed

1. Read the in the data: lending_data.csv
2. Split data into training and test sets
3. Created, Fit and Compared Models

## Summary:
The Random Forest Classifier performed only slightly better than the Logistic Regression which is not the result expected. Upon further review the Random Forest Classifier performs both regression and classification which could explain why it performed slightly better. However, I did note that the Random Forest Classifier ran slower than the Logistic Regression. So, since they both preformed with training and testing scores in the 99th percentile, I would choose to use the Random Forest Classifier because it executes faster.
