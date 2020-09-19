![SSMS](readme-resources/spam-sms-banner.png)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![library](https://img.shields.io/badge/Library-nltk,_sklearn-orange.svg)

## Project Overview
• Created a machine learning model that **detects/classifies a SMS based on the textual data using Natural Language Processing.**<br/>
• **Engineered features like word_count, contains_currency_symbol, and contains_number** from the text SMS.

## How will this project help?
• This project **helps in filtering/cleaning the SMS from the phone.**

## Resources Used
• Packages: **pandas, numpy, sklearn, matplotlib, seaborn, nltk.**<br/>
• Dataset by **UCI Machine Learing on Kaggle**: https://www.kaggle.com/uciml/sms-spam-collection-dataset

## Exploratory Data Analysis (EDA)
• **Exploring NaN values** in dataset
• **Plotted countplot** for SMS labels Spam vs. Ham<br/>

## Feature Engineering
• Handling imbalanced dataset using Oversampling
![SpamVsHam](readme-resources/svh.png)<br/>
• **Creating new features** from existing features e.g. **word_count, contains_currency_symbol, contains_numbers**, etc.<br/>
![jih](readme-resources/jih.png)<br/>
• Trimming columns i.e. **Trimming features having more than 10 categories to reduce the dimensionality**<br/>
• **Handling ordinal and nominal categorical features**<br/>
• Feature Selection using **information gain (mutual_info_regression) and correlation matrix**<br/>
![infogain](readme-resources/infogain.png)<br/>
![corr1](readme-resources/corr1.png)<br/>
• Feature Scaling using **StandardScalar**

## Data Cleaning

## Model Building and Evaluation
Metric: Negative Root Mean Squared Error (NRMSE)<br/>
• Multiple Linear Regression: -27.523<br/>
• Lasso Regression: -27.993<br/>
• **Random Forest: -17.637**<br/>
• Gradient Boosting: -24.429<br/>
• Voting (Random Forest + Gradient Boosting): -19.136<br/>
_**Note: Evaluation scores are obtained using cross validation.**_

## Model Prediction
![Prediction](readme-resources/prediction.PNG)
