---
title: "twarc Utilities"
author: Amelia Meyer
date: 03/02/2021
output: html
---
##### Table of Contents  
[Filtering](#headers)  
[Extraction](#extraction)  
[Visualization](#visualization)  
[Status](#status)  
[Organization](#organization)  
[System](#system) 
[Extra Resources](#extraresources) 

...snip...   
<a name="headers"/>
## [Filtering](filtering_utilities.md)
  - deduplicate.py: filters out duplicate ids from tweets
  - filter_date.py: filters tweets by date supplied
  - filter_users.py: filters tweets by user
  - gender.py: filters tweets by gender
  - geo.py: filters tweets by presence or absence of geo coordinates
  - geofilter.py: filters tweets by presence or absence of geo coordinates
  - noretweets.py: filters out retweets from tweets 
  - sensitive.py: filters tweets by presence or absence of possibly sensitive content
  - search.py: filters tweets by regular expression given
  - twarc-archive.py: filters tweets by specific word supplied
  - webarchives.py: filters tweets by presence or absence of webarchive

## [Extraction](extraction_utilities.md)
  - embeds.py: extracts list of media urls
  - emojis.py: extracts emojis and number of times used
  - extractor.py: overall extractor of attributes
  - flakey.py: extracts creation times for snowflake ids
  - media_urls.py: extracts id and url of images
  - media2warc.py: saves media to warc 
  - retweets.py: extracts original tweet id and number of times retweeted
  - tags.py: extracts hashtags and number of times used
  - times.py: extracts times tweets were made
  - tweets.py: extracts id, time, tweet text,...
  - tweetometer.py: extracts supplied tweet attributes to csv
  - tweet_text.py: extracts username and full text
  - tweet_urls.py: extracts urls
  - users.py: extracts user names/screen names

## [Visualization](visualization_utilities.md)
  - geojson.py: creates a geojson file that can be used for geo visualization
  - json2csv.py: creates a csv of tweets
  - network.py: creates a static D3 network of tweets
  - source.py: creates a page of which twitter client sources are msot used
  - wall.py: creates a wall of tweets
  - wordcloud.py: creates a wordcloud of tweets

## [Status](status_utilities.md)
  - deleted.py: checks the status of each tweet, outputting tweets that have been deleted
  - deletes.py: takes deleted tweet output and determines why tweet/user was deleted
  - deleted_users.py: checks the status of each tweet, outputting tweets/users that have been deleted
  - foaf.py: finds the friend of a friend network for a particular user	
  - oembeds.py: reads a stream of tweet JSON and augments .entities.urls with oembed metadata for the URL
  - tweet.py: fetches tweet from twitter stream using tweet id, if it exists
  - tweet_compliance.py: provides most recent version of a tweet, if it exists
  - wayback.py: reads stream of tweets and checks whether that tweet is archived at Internet Archive

## [Organization](organization_utilities.md)
  - sort_by_id.py: sorts tweets by id
  - unshrtn.py: unshortens urls 
  - urls.py: takes unshorted urls and prints them out
  - youtubedl.py: uses youtube-dl to download video content in tweets


## [System](system_utilities.md)
  - auth_timing.py: allows search 450 requests every 15 minutes, and User Auth contexts at 180 requests per 15 minutes
  - remove_limit.py: removes limit warnings from API
  - validate.py: removes unused imports

## Extra Resources

