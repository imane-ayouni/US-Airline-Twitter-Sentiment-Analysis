# US-Airline-Twitter-Sentiment-Analysis

## Topic

When we talk about  Natural Language Processing, we basically refer to making computers able to process human language, and more importantly understand it and take actions based on it. This language can be text based or audio based. 

Sentiment Analysis – One of the most popular projects in the industry. Every customer facing industry (retail, telecom, finance, etc.) is interested in identifying their customers’ sentiment, whether they think positive or negative about them.

The dataset contains more than 14000 tweets data samples about six airline companies, classified into 3 types: positive, negative, neutral. It contains information such as :

- Tweet id : identification number of the tweet
- airline sentiment : the general sentiment the client has about the company i.e :positive, negtive or neutral
- airline sentiment confidance : how confidant is the client about their opinion
- negative reason : the reason why the subject had a negative experience
- negative reason confidance : how confidant the subject is about their negative reason
- airline : the name of the company reviewed
- retweet count : how many time was the tweet retweeted
- text : the actual comment the client wrote
- the time, time zone and geolocation of the tweet


## Objectives

- Clean and process the data using NLP techniques
- Build and experiment different models able to analyse the sentiment of a tweet.
- Compare models' performances and choose the best one for this project



## Models Used :
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- SVM Classifier


## Evaluation matrices
- ROC Curve
- Classification Report
- Accuracy, Precision and Recall scores



## Data Source
https://www.kaggle.com/crowdflower/twitter-airline-sentiment
