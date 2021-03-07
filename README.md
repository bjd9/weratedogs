## WeRateDogs Twitter Analysis @dogs_rates

###Introduction
WeRateDogs (under the Twitter handle @dog_rates) is an account focused on rating dog's often with  photos, commentary and a rating, done in a light, entertaining spirit.

Project focuses on data wrangling focusing on tidiness issues and data quality from raw data files. It includes storing, analyzing and visualizing the data. And finally, producing an internal report on data wrangling efforts and a public facing report on data analyses and visualizations.

###Data Sources:
* `twitter_archive` : WeRateDog Twitter archive data provided file to be imported via pandas. This contains basic tweet data for all tweets as of August 1, 2007.
* `image_predictions` : Top 3 image predictions of each tweet (goal of predicting the breed of dog shown) according to neural network. The file ('image_predictions.tsv') is hosted on Udacity's server and downloaded using the request library via provided url.  
* `tweet_data` : Using tweet IDs in 'twitter_archive', query Twitter API for each tweet's JSON data using tweepy library and store each tweet's entire set of JSON data in a file 'tweet_json.txt'.

Python3 was used for the wrangling efforts with the assistance of the following libraries:
* pandas
* NumPy
* requests
* tweepy
* JSON
* seaborn

###Data Assessing:

###Products:
* Data Wrangling [Jupyter Notebook, HTML] or [Jupyter Notebook, pdf]
* Report, Data Wrangling [PDF]
* Report, Analysis & Visualizations [PDF]

###Reference:
