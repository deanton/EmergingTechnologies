# EmergingTechnologies
Analyzing perception of Twitter users in regard to emerging technologies

keywords directory contains files with the keywords used to collect and categorize the tweets (one file for each emerging technology category)
emerging_tweets-anon-sample.csv: is a sample of the first 100 tweets of the dataset (tab separated)
emerging_tweets-anon.csv.gz: the anonymized dataset (tab separated)

fields: 
tweet_id: anonymized tweet id
date: of the tweet
retweet: boolean, 1 if tweet is retweet
Additive Manufacturing: boolean, 1 if tweet belongs to category 
Artificial Intelligence: boolean, 1 if tweet belongs to category
CryptoCurrencies: boolean, 1 if tweet belongs to category
Computing Infrastructure: boolean, 1 if tweet belongs to category
Digital Health: boolean, 1 if tweet belongs to category
Internet of Things: boolean, 1 if tweet belongs to category
Quantum Computing: boolean, 1 if tweet belongs to category
Robotics: boolean, 1 if tweet belongs to category
Autonomous Vehicles: boolean, 1 if tweet belongs to category
Hashtags: included in the tweet
lat: latitude if exists, Null if not
lon: longitude if exist, Null if not
Country: extracted country information from tweeting user profile
Sentiment Score
Sentiment: POS|NEU|NEG
anger: number of words indicating anger emotion / total number of words indicating emotion
anticipation: number of words indicating anticipation emotion / total number of words indicating emotion
disgust: number of words indicating disgust emotion / total number of words indicating emotion
fear: number of words indicating fear emotion / total number of words indicating emotion
joy: number of words indicating joy emotion / total number of words indicating emotion
negative: number of words indicating negative emotion / total number of words indicating emotion
positive: number of words indicating positive emotion / total number of words indicating emotion
sadness: number of words indicating sadness emotion / total number of words indicating emotion
surprise: number of words indicating surprise emotion / total number of words indicating emotion
trust: number of words indicating trust emotion / total number of words indicating emotion
URLs: included in the tweet
followers: number of followers of the user at the time of collection
friends: number of friends of the user at the time of collection
statuses: number of statuses of the user at the time of collection
