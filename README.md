# Tweepy to Mongo.
- Create a python script that uses the Tweepy library to pull Tweets with specific keywords from Twitter's Streaming API, and then stores the important fields from the Tweet in a MongoDB collection.
- The API that I have used is called Twitter Streaming API which will give you real-time data from 8 hours to present. The Twitter Streaming API is ideal for grabbing data in real-time and storing it for analysis


### Dependencies:
- Tweepy
- Pymongo 
- MongoDB 

### Setup:
- Have MongoDB installed on localhost, and create a database called TwitterStream
- Open the script and add the keywords or hashtags you want to track to the "keywords" variable
- Watch as tweets are collected in real time and getting stored in MongoDB.


### Extras:
The comments inside the script are detailed and tells you the parts which you need to edit (like putting your own keys or renaming the database) and also tells you the part which you are not suppose to touch.


