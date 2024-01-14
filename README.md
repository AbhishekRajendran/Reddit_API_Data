# Reddit API Data Extraction and Text Analysis Project



## Table of Contents

1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Analysis Steps](#analysis-steps)


## Introduction

This project aims to analyze and extract insights from Reddit posts in the domains of Data Science, Artificial Intelligence, and Machine Learning. The analysis includes retrieving top posts from specified subreddits, extracting comments, and exploring comment structures.

## Setup 

### For DATA extraction

Obtain Reddit API Credentials
To access the Reddit API, you need to create a Reddit application and obtain the necessary credentials. Follow these steps:

Go to Reddit Apps page
Scroll down to the "Developed Applications" section
Click on "Create App" or "Create Another App"
Choose the application type (script, web app, etc.)
Fill in the required information
Note down the client_id and client_secret
For more details, refer to the Reddit API documentation.

Python Libraries Used:

praw: This library is used to interact with the Reddit API. It allows you to fetch information about subreddits, posts, comments, and more.

pandas: Used for data manipulation and analysis. The fetched data from Reddit will be organized into a Pandas DataFrame for easy handling.

Note:
This script is a reference for fetching top posts from specified subreddits based on the time filter. Customize it according to your needs.
For a more in-depth understanding of the used libraries, refer to the official documentation: praw documentation and pandas documentation.

### For text data analysis

pandas: A powerful data manipulation and analysis library.

datetime: A module to work with dates and times.

matplotlib: A plotting library for creating static, interactive, and animated visualizations.

seaborn: A statistical data visualization library based on Matplotlib.

WordCloud: A library for creating word clouds.

transformers: A library from Hugging Face for natural language processing (NLP) using pre-trained transformer models.

plotly: A graphing library for creating interactive, publication-quality graphs and dashboards.

huggingface/transformers: Hugging Face's Transformers library for working with transformer-based models.

wordcloud: A library for creating word clouds.

torch: PyTorch, an open-source deep learning library.

bhadresh-savani/distilbert-base-uncased-emotion: A Hugging Face model for emotion analysis using DistilBERT.

facebook/roberta-hate-speech-dynabench-r4-target: A Hugging Face model for hate speech classification using RoBERTa.

## Usage
