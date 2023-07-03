# Twitter Sentiment Analysis

This project focuses on sentiment analysis of tweets using Twitter's developer APIs, the Tweepy library, SQLite database, Flask, and VADER (Valence Aware Dictionary for Sentiment Reasoning). The objective is to scrape tweets, store them in a SQLite database, perform sentiment analysis using VADER, and apply various preprocessing techniques.

## Technologies Used

- Twitter Developer APIs: Twitter provides APIs that allow developers to access and interact with Twitter data programmatically.
- Tweepy Library: Tweepy is a Python library that simplifies the process of accessing Twitter's developer APIs and retrieving tweets.
- SQLite Database: SQLite is a lightweight, serverless database engine that allows for efficient storage and retrieval of structured data.
- Flask: Flask is a web framework for Python that enables the creation of web applications.
- VADER: VADER is a lexicon and rule-based sentiment analysis tool specifically designed for social media text. It provides sentiment scores based on the presence of specific words and phrases.

## Project Workflow

1. **Twitter Scraping**: The project starts with the utilization of Twitter's developer APIs and the Tweepy library to scrape tweets. The API allows access to real-time or historical Twitter data based on specified search queries or user profiles.

2. **Data Storage**: The scraped tweets are stored in a SQLite database. SQLite provides a lightweight and self-contained database solution that can be easily integrated into the project.

3. **Sentiment Analysis**: The stored tweets are subjected to sentiment analysis using VADER. VADER assigns sentiment scores (positive, negative, or neutral) to individual tweets based on the presence of words and phrases with known sentiment values.

4. **Preprocessing Techniques**: Various preprocessing techniques are applied to the tweets before sentiment analysis. These techniques can include tokenization, lowercasing, removal of stop words, punctuation, and special characters, as well as stemming or lemmatization.

5. **Web Interface**: The project includes a web interface built with Flask, allowing users to interact with the sentiment analysis results. Users can enter queries or view sentiment analysis statistics through the web interface.

## Installation and Usage

To run this project locally, follow these steps:

1. Clone the project repository from GitHub.
2. Install the required dependencies using `pip` or `conda`.
3. Set up the Twitter developer API credentials and obtain the necessary access tokens.
4. Set up the SQLite database and establish the connection.
5. Run the Flask application to start the web interface.
6. Access the web interface through the provided URL and interact with the sentiment analysis results.

Please refer to the project documentation or the README file in the repository for detailed installation instructions and usage guidelines.
