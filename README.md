# WeRateDogs twitter archive analysis

## Introduction
this project aims to gather, assess, and clean data then act on it through analysis, visualization and modeling.

> ## Project parts 

* twitter_archive_enhanced.csv: The WeRateDogs Twitter archive.
* The tweet image predictions: What breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on [Udacity](https://www.udacity.com/)'s servers and should be downloaded programmatically using the Requests library and the following [URL](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv).
* tweet_json.txt file: Using the tweet IDs in the WeRateDogs Twitter archive, I queried the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in that file. Each tweet's JSON data is written to its own line. 

> ## Project output 

* wrangle_report.pdf: documentation for data wrangling steps: gather, assess, and clean
* act_report.pdf: documentation of analysis and insights into final data
