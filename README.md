# Udacitiy_Project4_WeRateDogs
<br>
## General information
The data was provided by the twitter user @WeRateDogs, Udacity and additional information was gathered from the twitter API. This project is part of Udacity’s Data Analyst Nanodegree program. 
<br><br>
## Information about the data
<br>
I was provided with 2 files directly from Udacity: a .csv file (archive.csv) and a .tsv file (predictions.tsv). I downloaded them both programmatically to ensure reproducibility. The third file was gathered using the twitter API and saved to a json file (tweet_json.txt). 
Archive.csv is a collection of tweets that was provided by @WeRateDogs and contains information about the tweet like text, rating and the dog categorization they use (doggo, floofer, pupper, puppo). 
Predictions.tsv contains information gathered from @WeRateDogs using a neural network to predict the dog breed in the image @WeRateDogs posts together with their tweets. 
Tweet_json.txt contains all additional information I could gather using the tweepy, the twitter API. I mostly use retweet_count and favorite_count as an addition to the existing dataset.

