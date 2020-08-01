# Stock Price Prediction by Sentiment Analysis on News Headlines

## Objective
Build a model to predict if the stock price of a company will increase or decrease based on top news headlines.

## Data
### Source: https://www.kaggle.com/aaron7sun/stocknews

### Description:
There are two channels of data provided in this dataset:
- News data
  - Historical news headlines from Reddit WorldNews Channel (/r/worldnews).
  - These are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date.
  - News ranges from 2008-06-08 to 2016-07-01

- Stock data
  - Dow Jones Industrial Average (DJIA) stock data is used
  - Stock data ranges from 2008-08-08 to 2016-07-01
  
## Approach
- This is a classification problem
- Collect all top news headlines for that stock
- Perform sentiment analysis on the news headlines
- If the sentiment is positive then the price of the stock should rise and it should fall if the sentiment is negative

## Sentiment Analysis and Modelling
In this project I have utilised the following methods/models for our analysis
- CountVectorizer
- TfidfVectorizer
- RandomForestClassifier
- Naive Bayes
- TextBlob
- SentimentIntensityAnalyzer
- LinearDiscriminantAnalysis
