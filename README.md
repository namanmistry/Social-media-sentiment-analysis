# Project Title

Social Media Sentiment Analysis

## Project Description

This project aims to analyze the sentiment of social media users towards trending topics on platforms such as Twitter, Reddit and YouTube. The goal is to determine whether people are reacting positively or negatively to the topic.

## File Structure

1. `model_making.ipynb`: This file contains the code to make a sentiment prediction model using transformers from scratch (using TensorFlow). The model was trained on Twitter data (1.6 million posts for 5 epochs). You can run this file to make a model and train it from scratch, and you can also use other datasets and experiment as well.

2. `Data_gathering_and_testing.ipynb`: This file contains the code to gather data from Twitter (using the API), Reddit, and YouTube. This will get the data for the sentiment analysis.

3. `model_testing.ipynb`: This file contains the final code that will load the trained model and will create visualizations on the social media data live by fetching the data when you run the code.

Please note: You need a Twitter developer account to get the data from the API, and you also need to create an app on Reddit to run all of these. For getting YouTube data, you do not need anything, and you can run it directly.

## Setup

1. You need to create a virtual environment using the `requirements.txt` file.
2. Then, you need to set up your credentials for APIs.

## Author

Naman Mistry
