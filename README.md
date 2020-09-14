<img src="https://i.ibb.co/ZXVNVY5/pr-logo-plain-opauq.png" width="7.5%" height="7.5%">

# Pundits Review Sentiment Prediction
Development of the prediction model for the Pundits Review website used to predict the sentiment in football news articles - https://www.punditsreview.com/


> Pundits Review scrapes and processes news articles about the Premier League in order to give players and teams a review score each week. Each Monday, the project collects articles, divides them into phrases, identifies the player or club being referred to and then predicts the sentiment of the phrase. See more on how it works <a href="https://www.punditsreview.com/howitworks">here</a>!


## About this repository
This repository shows the progression of the methods used to train a model to predict the sentiment of phrases within a football news article. Attempts 1 & 2 use general sentiment datasets whereas 'Building the model' uses <a href="https://github.com/charlesmalafosse/open-dataset-for-sentiment-analysis">football specific sentiment data</a> from <a href="https://betsentiment.com/">BetSentiment.com</a>. My final training data is provided alongside the methods used to pre-process it.

## Contents

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Sentiment-Prediction/blob/master/1st_Attempt.ipynb">Attempt 1</a>
Attempt 1 trains a Linear Regression sentiment model on a twitter sentiment dataset provided by Stamford University

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Sentiment-Prediction/blob/master/2nd_Attempt.ipynb">Attempt 2</a>
Attempt 2 trains a Linear Regression sentiment model on a <a href="https://raw.githubusercontent.com/kolaveridi/kaggle-Twitter-US-Airline-Sentiment-/master/Tweets.csv">airlines sentiment dataset - Kaggle</a>

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Sentiment-Prediction/blob/master/Building_the_model.ipynb">Building the Model</a>
Notebook used to build different models using BetSentiment data

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Sentiment-Prediction/blob/master/Preprocessing.ipynb">Preprocessing</a>
Notebook used to clean and preprocess the training data

#### <a href="https://github.com/andyclarkemedia/Pundits-Review-Sentiment-Prediction/blob/master/training_data.csv">Training Data</a>
Training data used to train different model approaches in 'Building_the_model' - After preprocessing


## Associated Repositories

##### <a href="https://github.com/andyclarkemedia/Pundits-Review">Pundits Review</a> - 11/09/2020 - Complete directory for Pundits Review web application.
##### <a href="https://github.com/andyclarkemedia/Pundits-Review-Resources">Resources</a> - Data, images & Python dictionary of Premier League players & teams
##### <a href="https://github.com/andyclarkemedia/Pundits-Review-Scraping">Scraping</a> - Development of the scraping process used to collect data
##### <a href="https://github.com/andyclarkemedia/Pundits-Review-Entity-Extraction">Entity Extraction</a> - Development of the process used to recognise Premier League player & club entities within a news article

##
#### Any Questions ... <a target="_blank" href="mailto:clarkeAJ3@cardiff.ac.uk">Send me an email!</a>
