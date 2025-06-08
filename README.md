# Sentiment-Analysis-Group_10

## Introduction

This project focuses on building a text classification system for sentiment analysis. The goal is to compare the effectiveness of a traditional machine learning model and a deep learning model in analyzing sentiment from text data.

We selected the [amazon_polarity](https://huggingface.co/datasets/fancyzhx/amazon_polarity) dataset from Hugging Face and performed comprehensive exploratory data analysis (EDA) to understand its characteristics. The data underwent extensive text preprocessing, including tokenization, removal of stopwords, and embedding using techniques like TF-IDF, Word2Vec, and GloVe.

1. Dataset Overview
Dataset URL: [Amazon Polarity Dataset on HuggingFace](https://huggingface.co/datasets/fancyzhx/amazon_polarity)

This dataset contains Amazon product reviews with binary sentiment labels:

1: Positive

0: Negative

2. Exploratory Data Analysis (EDA)

   a. Basic Statistics
   
Number of reviews

Distribution of sentiment classes

Average review length (in words or characters)

Vocabulary size

b. Visualizations
Word cloud for positive and negative reviews

Class distribution bar chart

Histogram of review lengths

3. Preprocessing Steps
a. Cleaning
Remove HTML tags, punctuation, and special characters

Convert to lowercase

Remove extra whitespace

b. Tokenization
Split text into tokens using NLTK or spaCy

c. Stopword Removal
Remove common stopwords (e.g., “the”, “and”, "is") using NLTK
 

## Local Development Setup.

Clone the repository or download these files to run in your collab.

Traditional model: [traditional_model](https://colab.research.google.com/github/RainiBenaiah/Sentiment-Analysis-Group_10/blob/main/sentiment_analysis_traditional_modelGP10.ipynb)

Deep learning model: [deep_learn.ipynb…](https://colab.research.google.com/drive/1Sg1euYF2ozZi7yL7EDe9qox9dKUqdDYN?usp=sharing&authuser=1)
                     [deeplearn.ipynb…](https://colab.research.google.com/drive/1ezM9LVOnaWCyarRsSlDfLq7LuVJVd0IA?usp=sharing)
                     


