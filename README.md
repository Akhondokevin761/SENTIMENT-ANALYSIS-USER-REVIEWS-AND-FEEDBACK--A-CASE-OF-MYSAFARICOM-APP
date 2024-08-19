# SENTIMENT-ANALYSIS-USER-REVIEWS-AND-FEEDBACK--A-CASE-OF-MYSAFARICOM-APP

## Table of Contents
-[Introduction](#Introduction)

-[Installation](#Installation)

-[Data](#Data)

-[Model Training and Testing](#Model-Training-and-Testing)

-[Model Deployment](#Model-Deployment)






## Introduction

In today's world, it is important to analyze texts and comments from people, and more importantly, product users in a digital setting. These are reviews. Such can be either positive or negative and are called sentiments.

Sentiment Analysis is a technique that businesses are using to analyze customer feedback about their products. Python is commonly used in such text analysis tasks to execute this. The Natural Language Toolkit (NLTK) Library in Python is widely used.

In this repository, we will not use NLTK Library, but rather, train two machine learning algorithms, Logistics Regression and Support Vector Machines using the Google Play Store user review dataset. The models are tested using the test data and the one with the highest accuracy is applied to Mysafaricom app customer review data that is scrapped from Google Playstore.

The sentiments are then classified as either Positive or Negative. The final Excel CSV file containing the review and sentiment is Safaricomreviewsfinal which can be opened by MS Excel.

## Installation

Python 3 is used. Ensure the following libraries are downloaded and loaded:

- pandas
- Numpy
- NLTK
- Google Play Scraper
- sklearn
- pickle
- joblib
- textwrap
- matplotlib
- os


## Data

The test and train data is User Review found in the Data folder. This data contains 64295 observations and 5 variables which makes it perfect for train and test of a machine-learning model. The data is Preprocessed in Excel by deleting 3 variables to remain with Translated_Review and Sentiment. The Tranlated_Review is renamed to review and the Sentiment to review. All these steps are done in MS Excel.

The model is applied on MySafaricom App customer review data, which is scrapped from Google Playstore.


## Model Training and Testing
