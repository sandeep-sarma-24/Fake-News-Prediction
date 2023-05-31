# Fake News Prediction: Logistic Regression with TF-IDF Vectorizer

This project aims to predict whether a news item is fake or real using a Logistic Regression model and a TF-IDF Vectorizer.

## Project Overview

In the age of the internet, we are constantly bombarded with information. Among this deluge of news and reports, unfortunately, are fake news articles. These false reports can be misleading and even dangerous. Our goal with this project is to use machine learning to distinguish between real and fake news.

## Methodology

Our project uses the Term Frequency-Inverse Document Frequency (TF-IDF) Vectorizer to transform the text data into a format that can be used by our Logistic Regression model. 

Logistic Regression is a machine learning algorithm that is well-suited to binary classification problems. It uses the logit function to find a model that fits with the data points and makes predictions about whether an input falls into one of the two classes.

## Dataset

The dataset used in this project consists of news articles labeled as either "fake" or "real". For each article, we have the title, text, and label. 

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- sklearn
- matplotlib
- seaborn

## Usage

1. Clone the repository: `git clone https://github.com/username/fake-news-prediction.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Run the script: `python main.py`

## Results

We found that our model had a prediction accuracy of 97.90%, showing that it is quite effective in distinguishing between real and fake news.

