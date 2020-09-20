![SSMS](readme-resources/spam-sms-banner.png)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![library](https://img.shields.io/badge/Library-nltk,_sklearn-orange.svg)

## Project Overview
• Created a machine learning model that **detects/classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.**<br/>
• **Engineered features like word_count, contains_currency_symbol, and contains_number** from the text SMS.

## How will this project help?
• This project **helps in filtering/cleaning the SMS from the phone.**

## Resources Used
• Packages: **pandas, numpy, sklearn, matplotlib, seaborn, nltk.**<br/>
• Dataset by **UCI Machine Learing on Kaggle**: https://www.kaggle.com/uciml/sms-spam-collection-dataset

## Exploratory Data Analysis (EDA)
• **Exploring NaN values** in dataset<br/>
• **Plotted countplot** for SMS labels Spam vs. Ham

## Feature Engineering
• Handling imbalanced dataset using Oversampling<br/>
![SpamVsHam](readme-resources/svh.png)<br/>
• **Creating new features** from existing features e.g. **word_count, contains_currency_symbol, contains_numbers**, etc.<br/>
![word_count](readme-resources/word_count.png)<br/>
![currency_numbers](readme-resources/currency_numbers.png)

## Data Cleaning
• Removing special character and numbers using regular expression<br/>
• Converting the entire sms into lower case<br/>
• Tokenizing the sms by words<br/>
• Removing the stop words<br/>
• Lemmatizing the words<br/>
• Joining the lemmatized words<br/>
• Building a corpus of messages

## Model Building and Evaluation
**Metric: F1-Score**<br/>
• Multinomial Naive Bayes: 0.943<br/>
• Decision Tree: 0.98<br/>
• **Random Forest: 0.994**<br/>
• Voting (Decision Tree + Multinomial Naive Bayes): 0.98<br/>
![matrix](readme-resources/cm.png)<br/>
_**Note: Evaluation scores are obtained using cross validation.**_

## Model Prediction
![Prediction](readme-resources/prediction.PNG)

## Model Deployment
• Repository Link: https://github.com/anujvyas/Spam-SMS-Classifier-Deployment<br />
• Web App Link: https://spam-sms-detector.herokuapp.com/<br/>

_**Do ⭐ the repository, if it helped you in anyway.**_
