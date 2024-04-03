# SMS Spam Classification Model

## Overview
This project focuses on developing a text classification model in Python to classify SMS messages as either spam or non-spam (ham). The dataset contains 5573 SMS messages, with a majority being ham (86.6%) and the rest being spam (13.4%). The goal is to build a machine learning model that can accurately distinguish between spam and ham messages.

## Dataset
The dataset consists of 5573 SMS messages labeled as spam or ham. The majority class is ham, accounting for 86.6% of the data, while the minority class is spam, representing 13.4% of the dataset. Each SMS message is a text string.

## Data Preprocessing
Data preprocessing involves removing any irrelevant columns and handling missing values, if any exist. Additionally, text data may require cleaning, such as removing punctuation and converting text to lowercase.

## Training Data Preparation
After preprocessing, the dataset is split into training and testing sets while maintaining the original class distribution. This ensures that both sets contain a proportional representation of spam and ham messages.

## Model Training
A machine learning pipeline is created using scikit-learn. The pipeline consists of a CountVectorizer for feature extraction and a K-Nearest Neighbors (KNN) classifier for classification. CountVectorizer converts text data into numerical feature vectors, while KNN is trained to classify messages as spam or ham based on these feature vectors.

## Result
The trained model is evaluated on both training and testing sets using accuracy as the performance metric. The CountVectorizer with KNN classifier notably outperforms the TF-IDF Vectorizer with KNN in terms of accuracy. The model achieves an accuracy of 97.3% on the training set and 96.8% on the test set, demonstrating its reliability and effectiveness in classifying SMS messages. Despite the imbalanced class distribution, the model accurately distinguishes between spam and ham messages.
