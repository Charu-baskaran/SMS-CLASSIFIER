# SMS Spam Classification Model

## Overview
This project focuses on developing a text classification model in Python to classify SMS messages as either spam or non-spam (ham).The goal is to build a machine learning model that can accurately distinguish between spam and ham messages.

## Dataset
The dataset consists of 5573 SMS messages labeled as spam or ham. The majority class is ham, accounting for 86.6% of the data, while the minority class is spam, representing 13.4% of the dataset. Each SMS message is a text string.

## Data Preprocessing
Data preprocessing involves removing any irrelevant columns and handling missing values, if any exist. Additionally, text data may require cleaning, such as removing punctuation and converting text to lowercase.

## Visualizations
Catplot: Visualizes the distribution of spam and ham messages.
Pie Chart: Illustrates the proportion of spam and ham messages in the dataset.
Confusion Matrix: Displays the performance of the classification model, showing the true positives, true negatives, false positives, and false negatives.

## Result
The trained model is deployed as a streamlit app, which takes input text and predicts whether it is spam or not spam.
