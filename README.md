# WeRateDogs
Data Wrangling and Analysis Project on Twitter account


## Introduction

Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. 
The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 

## Installing

The following packages (libraries) need to be installed. 
  - NumPy
  - requests
  - tweepy
  - json
  - matplotlib
  - Need consumer_key, consumer_secret, access_token, access_secret to query from Twitter API.

## Files

- 'wrangle_act.ipynb': The main file containg data wrangling process
- 'wrangle_report': decribing data wrangling efforts
- 'act_report': communicating insights with visualization on wrangled data
- '

## Key Points
Key points to keep in mind when data wrangling for this project:

- You only want original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.
- Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
- Cleaning includes merging individual pieces of data according to the rules of tidy data.
- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.
- You do not need to gather the tweets beyond August 1st, 2017. You can, but note that you won't be able to gather the image predictions for these tweets since you don't have access to the algorithm used.

## Project Details

our tasks in this project are as follows:

- Data wrangling, which consists of:
     - Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
     - Assessing data
     - Cleaning data
- Storing, analyzing, and visualizing your wrangled data
- Reporting on 1) your data wrangling efforts and 2) your data analyses and visualizations
