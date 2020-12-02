Analyzing Airline Tweets

Introduction

Within the past few months, many businesses faced unprecedented complications due to the COVID-19 pandemic.  Important business decisions had to be made quickly and without the knowledge of how long the pandemic may last.  One of the industries faced with these difficult decisions was the airline industry.

Commercial aviation has a large impact on the U.S. economy.  More than 5% of the U.S. GDP growth and over 10 million jobs are created by this industry.  The business decisions made by this industry have a far-reaching impact, so it is important for decision makers to have access to timely and comprehensive information.  In order to survive the pandemic, the airline industry will need to use this information to radically restructure itself.  

Many people have strong opinions about the airline industry.  Whether they are upset about the customer service, flight disruptions, or the gradually shrinking seating space, people willingly broadcast their sentiments on social media platforms.  This data can be useful to gauge how customers feel towards the airline industry during the pandemic.  If customers do not feel safe to use their services, many airlines may not survive, and our economy will be affected.

Analysis and Models

About the Data

The data consisted of a CSV file with 14,640 tweets labeled as positive, neutral, or negative.  The distribution of the tweets are 16.1% are positive, 21.2% are neutral, and 62.7% are negative.

Considering there were significantly more negative tweets than neutral or positive, the models were trained on the original data and a subset of the data that had an equal amount of each label.

The data was vectorized three different ways.  The first was a unigram frequency distribution, the second was a binary frequency distribution, and the third was a unigram tfidf.  Next the data was divided into training and testing data with 60% of the data being used for training and 40% to be used for testing.


