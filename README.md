# Covid-19-Tweets-Sentiment-Analysis

## Problem:
This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets.The tweets have been pulled from Twitter and manual tagging has been done then.
The names and usernames have been given codes to avoid any privacy concerns.

## Approach and Presentation :

Final Notebook - https://github.com/yagnik99/Covid-19-Tweets-Sentiment-Analysis/blob/main/Capstone_Project.ipynb

Presentation - https://github.com/yagnik99/Covid-19-Tweets-Sentiment-Analysis/blob/main/Final%20Presentation.pdf

## Important works/ Conclusions:
Collected related Tweets by using Twitter API and the tweepy library and applied NLP preprocessing like tokenization, lemmatization, removing stopwords.
Generated document-word sparse matrix using Tfidf Vectorizer to build a multiclass classifier with Catboost giving a precision of 87% on validation data.
