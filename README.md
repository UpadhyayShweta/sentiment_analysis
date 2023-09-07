# sentiment_analysis
In this notebook we'll perform sentiment analysis on tweets to understand it's impact  on stocks  and crypto prices.

## Project scope:

### Conducting sentiment analysis on media sources to measure impact on stock and crypto prices
#### Team 1
Shwetha Upadhay (Project Lead/Manager)
Sophie-Pearl Degain 
Emma Xu
Saleha Jaweid

### Summary
For our project we will be focusing our analysis on twitter datasets to perform sentiment analysis (using NLP models) on these datasets and infer any impact on stock and crypto prices for the following list of assets: AAPL, TSLA, AMZN, BTC, DOGE. 

### Project Details
In this project, we have applied sentiment analysis and two statistical machine learning models, Random Forest and Support Vector Regression. These models are used to depict the correlation between the tweets which are extracted from twitter and stock market movements of a company. We have performed sentiment analysis of the twitter data based on a whole day to analyze the effect it has on stock market prediction. The models are evaluated and compared using RMSE (root mean squared error) values.

An overview of the process flow of our project is as follows:

Data Collection: The dataset for stock market data & tweets is collected fro Kaggle. In this step the preprocessing of the tweets such as removing stop words, hyperlink and other steps are carried out.
Data Processing: The rows which have missing values such as price/text values are further processed. The data along with the sentiment scores is divided into train and test data and is fed to the model.
Sentiment Analysis: The sentiment analysis of the tweet is carried out using Texblob. Here each tweet is given a sentiment score which determines if the tweet is positive, negative or neutral.
Applying Regression Models: To predict stock Market prices, we have used Random Forest and Support vector regression models in this project. We will be then using RMSE scores to validate the efficiency of our models and to analyze which model works better for the used dataset.