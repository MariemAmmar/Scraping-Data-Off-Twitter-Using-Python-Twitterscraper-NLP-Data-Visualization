# Twitter Text Analysis

## Overview
Scraping Data from Donald Trump's Twitter and creating visualizations with it has never been easier! I did this project a while back just to see what the results would be and I ended up thinking it was pretty cool.

This Python script is designed to perform text analysis on tweets obtained from Twitter using the twitterscraper library. The analysis includes tasks such as tokenization, stemming, removing stop words, and identifying the most frequently mentioned organizations and people.

## Dependencies

- `nltk`: Natural Language Toolkit for text processing tasks such as tokenization, stemming, and lemmatization.
- `spacy`: An open-source library for natural language processing tasks.
- `twitterscraper`: A tool for scraping tweets from Twitter without using the Twitter API.
- `pandas`: A powerful data manipulation library.
- `numpy`: A library for numerical computing.
- `re`: Regular expression operations for string manipulation.
- `datetime`: Library for manipulating dates and times.
- `matplotlib`: Library for creating static, animated, and interactive visualizations in Python.
- `seaborn`: Statistical data visualization based on matplotlib.

## Usage

1. Install the required dependencies by running:
2. Run the script.

## How it Works

1. The script first imports necessary libraries including NLTK, spaCy, and twitterscraper.
2. Tweets are scraped from Twitter using twitterscraper based on user or a specific phrase/word.
3. Text preprocessing tasks are performed on the scraped tweets including tokenization, stemming, and removing stop words.
4. The script then identifies the top words overall, top organizations mentioned, and top people mentioned in the tweets.
5. Finally, visualizations are generated using matplotlib and seaborn to display the results.

## Note

- Ensure you have proper permissions before scraping tweets from Twitter.
- Twitter's terms of service should be respected while using this script for data collection.


