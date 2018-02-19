# Automatic Detection of Hate Speech

Authors: Amy Hemmeter and Kirsty Ward

Summary: this is a project on automated detection of hate speech on Twitter using data collected by Zeerak Waseem. These Jupyter Notebooks were designed as tutorials for how to clean social media data, create various Pandas dataframes, run a Term-Frequency Inverse Document Frequency (TFIDF) analysis, perform Sentiment Analysis, use regular expressions to pull out other text variables, and finally run these variables through a neural network using keras. To follow all of the steps, start with Jupyter Notebook 1. Data Cleaning. Each of the subsequent steps in the analysis are also numbered. We include all of the csv files in case you want to start in the middle.

The second "fourth" notebook is a Naive Bayes classifier - written with no packages, from scratch. This has minimal preprocessing of the data, includes just a bag of words approach because it is much quicker than a neural network. This model has 87% accuracy. 

NOTE: We provide Notebook 0 to show how we queried the Twitter API to get the tweets and associated metadata, but we removed our Twitter security keys. To use this Notebook you must obtain your own API key, and set aside three hours for large amount of data to be queried from the twitter API. We have provided the csv needed to run the following Jupyter notebooks so that replicating this step can be skipped.
