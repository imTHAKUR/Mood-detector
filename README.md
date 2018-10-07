# IBM Watson Personality Insights Twitter Python Sample

[![Build Status](https://travis-ci.org/watson-developer-cloud/personality-insights-twitter-python.svg?branch=master)](https://travis-ci.org/watson-developer-cloud/personality-insights-twitter-python)

This sample shows how to get Twitter data using the [Twitter REST API](https://dev.twitter.com/rest/public) 
(via the [python-tweepy client library](https://github.com/tweepy/tweepy)) and submit it to the 
[Personality Insights Service](https://www.ibm.com/watson/services/personality-insights/).

For non-twitter samples and more details on how to setup your Personality Insights service in IBM Cloud see the [official 
Watson Developer Cloud samples](https://github.com/watson-developer-cloud).

## Setup

This sample was developed on Python 2.7.2 with the `python-tweepy` and `requests` libraries, installed via pip.

## Configuring your Twitter and Personality Insights Credentials

To configure the sample, edit `twitteranalyzer.py` to fill in your Twitter and Personality Insights Credentials. Instructions are provided in the `comments` in same file.

## Running the sample

Provide a twitter handle/screen name WITHOUT the leading @ sign.  Example:

    python twitteranalyzer.py jschoudt
