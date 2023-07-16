# WeRateDog_tweets_analysis
The aim of this project was to analyze tweet data from the WeRateDogs Twitter handle. After reading the given datasets into Pandas dataframes, I went on to get a Twitter developer account with elevated access in order to be able to use the Twitter API keys and access tokens. Tho getting twitter elavated access took about two weeks, I was able to query the needed tweet data after getting the elavated access using Tweepy python API and Twitter’s OAuth 2.0 authentication.
The tweets_enhanced dataset originally contained over 5000 tweets, but only half of them had ratings (which I needed for this analysis). There were a lot of issues with the dataset in terms of quality and tidiness. I was able to address many of those issues.
After data wrangling session, I was able to the answer the following questions:
What year(s) WeRateDogs trended the most on Twitter?
From a pretrained neural networks trained on the dataset that i was able to access the result output data, which of the models performed better?
What are the correlation among the public metrics variables such as quote_counts, reply_counts, retweet_counts?
