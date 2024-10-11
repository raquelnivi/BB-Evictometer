# Big Brother Evictometer

## Overview

The **Big Brother Evictometer** is a data-driven tool that predicts which contestant is likely to be evicted from reality TV shows like **Big Brother** based on X sentiment analysis. The project analyzes posts mentioning the contestants, scores them based on positive and negative sentiment, and uses the results to forecast eviction outcomes.

## Features

- **Tweet Collection:** Scrape tweets related to Big Brother contestants using the Twitter API.
- **Sentiment Analysis:** Perform sentiment analysis to categorize tweets as positive, negative, or neutral.
- **Predictive Model:** Weigh sentiment scores and tweet volumes to predict which contestant is at risk of eviction.
- **Real-Time Monitoring:** Update predictions dynamically as new tweets are collected.

## Requirements

Before running the project, make sure you have the following installed:

- **Python 3.x**
- **Tweepy** - (for X API interaction)
- **TextBlob or VADER** (for sentiment analysis)
- **Pandas, NumPy** (for data manipulation)
- **Scikit-learn** (for predictive modeling)