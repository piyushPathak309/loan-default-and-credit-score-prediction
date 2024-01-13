# loan-default-and-credit-score-prediction

# Introduction and problem statement :

In the ever-evolving landscape of financial services, the ability to predict and mitigate credit risk is paramount. Lending institutions, leverage predictive models to identify clients at risk of defaulting on loans. In this project i have ****devloped a model to predict default clients**** of LendingClub loans as well built ****credit scorecard**** to ****predict credit score****, delving into the importance, key features, and the transformative impact these predictive models have on lending practices.

# Dataset:

In this project, I worked with the public LendingClub data, with a size of ~1.8 GB, containing 1.6 millions of loans from 2007 to 2014, each of which has 150 associated features. My goal was to build a predictive model that can predict whether a loan will be default or not as well predicted credit score , in order to minimize the risks of loan defaults for the company. I also would like to find the most important factors in making decisions about lending.


# Tools and Technologies Used :

Python,Machine Learning,Sklearn,Pandas,Matplotlib,Seaborn,Numpy


# ML model:

Throughout this Project i have followed the whole life cycle of a Data Science Project as:
EDA(Exploring Data and Understanding features doing univariate analysis,Bivariate analysis,Finding Distribution) and Data Cleaning(Finding Types of Features,Duplicate values,Missing Values,Outlier Detection)
Feature Engineering((Imputting Missing Values,Outlier,handlingImbalanced)) and Feature Selection ,Feature Scaling
Model Selection
Model Building
Model HyperParameter Tuning
Model Evaluation(Testing)

I analyzed useful features and investigated the correlations among the features and between the features and the target variable. According to the Pearson correlations between the features and the target variable, the most important variables for predicting default include the loan interest rate, loan term, and debt-to-income ratio. I trained a logistic regression, a random forest, and a KNN to predict loan defaults and make loan-granting decisions. The models were all fine-tuned with grid search. I evaluated and compared the models using a cross-validated AUROC score on the training set. Finally, I found that all the three models have similar performance according to their AUROC scores on the training data. 
I eventually selected logistic regression because it ran the fast and returned an AUROC score of 0.70 on the test data.
