# Twitter US Airline Sentiment Analysis

Author: Subhajit Banerjee

### Overview:
Social Media has taken the world by surprise at a swift and commendable pace. With the advent of any kind of circumstances may it be related to social, political or current affairs the sentiments of people throughout the world are expressed through their help, making them suitable candidates for sentiment mining.\
Sentimental analysis becomes highly resourceful for any organization who wants to analyse and enhance their products and services. In the airline industries it is much easier to get feedback from astute data source such as Twitter, for conducting a sentiment analysis on their respective customers. The beneficial factors relating to twitter sentiment analysis cannot be impeded by the consumers who want to know the who’s who and what’s what in everyday life.\
In this project we are classifying sentiment of Twitter messages by exhibiting results of a machine learning algorithm using Python. The tweets are extracted and pre-processed and then categorizing them in neutral, negative and positive sentiments.

![Capture](https://user-images.githubusercontent.com/17608830/114521906-79d92700-9c60-11eb-9e30-c0fc65716841.PNG)

### Objective:
The objective here is to analyze how travelers mentioned their feelings on Twitter in February 2015.

### Important Files:
* Tweets.csv : Dataset
* tweets-sentiment-analysis.ipynb : Jupyter notebook file containing the sentiment analysis

### Methods and Tools
* Python
* numpy
* pandas
* seaborn
* WordCloud
* TfidfVectorizer & TfidfTransformer
* MLPClassifier, RandomForestClassifier & LGBMClassifier

### Accuracy score from different techniques:
* MLP Classifier : 0.7374
* Random Forest Classifier : 0.7418
* LGBM Classifier : 0.7780
