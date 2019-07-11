# CovFeeFee-Bitcoins
Problem overview- Bitcoin is the origin and the king of cryptocurrency. Because of its high volatility, its difficult to determine the future value, the value trends, factors that affect bitcoin value and other substitute cryptocurrency.

# What does the world feel about Bitcoin?
Project Inspiration-
Bitcoin is a very volatile cryptocurrency. Its value peaked to $20k in 2018 and is currently priced at $12,600/-
 
So what does the world feel about bitcoin?
	
# Project Objective-
Populate twitter feed, predict and analyze twitter sentiments on Bitcoin for the past 3 days to understand how the world feels about Bitcoin.
Insights-
1.	Prediction model accuracy of 0.89
2.	In the past week, Bitcoin value increased by 13%. Twitter sentiments (Next insight) align with change in bitcoin value
 
3.	While majority of tweets indicate neutral sentiments, 35% of twitter users feel positive about Bitcoin 
 
4.	35% of Americans feel positive about Bitcoin. 
 
# Inference/Recommendation-
1.	While majority of twitter users indicate neutral sentiments, a vast portion of our users feel positive and we hardly saw any negative sentiments.
2.	We therefore recommend investing in Bitcoin.

Project Scope/Limitations-
•	We considered Kaggle dataset to train and test a sentimental prediction model
•	Twitter API calls only provide 1000 feeds each day. Our analyses and insights are restricted to a total of 3000 twitter feeds.
Project steps-
1.	Use Kaggle data with sentiments and SKLearn model to test, train and split data
2.	Use word2vec and random forest classifiers to fit and test the model
3.	Perform an API call and generate live twitter feeds on bitcoin for the past three days (In “Dumps” folder)
4.	Use trained and tested model to predict twitter sentiments on the live twitter feeds
5.	Analyze sentiments of twitter feeds for the past 3 days

Resources/Links-
•	https://www.kaggle.com/varun08/imdb-dataset/downloads/labeledTrainData.tsv/data
•	Libraries- Python Pandas, numpy, beautiful soup, sklearn, random forest classifiers, genism-word2vec, wordcloud, nltk, re, tweepy
•	Technology- python, tableau
•	3000 tweets were pulled (July 6th, July 7th, & July 8th). 
•	https://public.tableau.com/views/UCSDBitcoinSentiment/SentimentDashboard?:embed=y&:display_count=yes&publish=yes&:origin=viz_share_link




