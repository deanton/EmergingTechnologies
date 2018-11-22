# EmergingTechnologies
Analyzing perception of Twitter users in regard to emerging technologies

## files
- keywords directory contains files with the keywords used to collect and categorize the tweets (one file for each emerging technology category)
- emerging_tweets-anon-sample.csv: is a sample of the first 100 tweets of the dataset (tab separated)
- emerging_tweets-anon.csv.gz: the anonymized dataset (tab separated)

## fields: 
1. tweet_id: anonymized tweet id
2. date: of the tweet
3. retweet: boolean, 1 if tweet is retweet
4. Additive Manufacturing: boolean, 1 if tweet belongs to category 
5. Artificial Intelligence: boolean, 1 if tweet belongs to category
6. CryptoCurrencies: boolean, 1 if tweet belongs to category
7. Computing Infrastructure: boolean, 1 if tweet belongs to category
8. Digital Health: boolean, 1 if tweet belongs to category
9. Internet of Things: boolean, 1 if tweet belongs to category
10. Quantum Computing: boolean, 1 if tweet belongs to category
11. Robotics: boolean, 1 if tweet belongs to category
12. Autonomous Vehicles: boolean, 1 if tweet belongs to category
13. Hashtags: included in the tweet
14. lat: latitude if exists, Null if not
15. lon: longitude if exist, Null if not
16. Country: extracted country information from tweeting user profile
17. Sentiment Score
18. Sentiment: POS|NEU|NEG
19. anger: number of words indicating anger emotion / total number of words indicating emotion
20. anticipation: number of words indicating anticipation emotion / total number of words indicating emotion
21. disgust: number of words indicating disgust emotion / total number of words indicating emotion
22. fear: number of words indicating fear emotion / total number of words indicating emotion
23. joy: number of words indicating joy emotion / total number of words indicating emotion
24. negative: number of words indicating negative emotion / total number of words indicating emotion
25. positive: number of words indicating positive emotion / total number of words indicating emotion
26. sadness: number of words indicating sadness emotion / total number of words indicating emotion
27. surprise: number of words indicating surprise emotion / total number of words indicating emotion
28. trust: number of words indicating trust emotion / total number of words indicating emotion
29. URLs: included in the tweet
30. followers: number of followers of the user at the time of collection
31. friends: number of friends of the user at the time of collection
32. statuses: number of statuses of the user at the time of collection
