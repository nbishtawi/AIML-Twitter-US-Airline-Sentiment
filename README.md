# Twitter US Airline Sentiment Analysis

## Overview
This project performs sentiment classification on tweets about U.S. airlines. Using natural language processing (NLP) and machine learning, the model predicts whether a tweet is **positive**, **neutral**, or **negative**. The analysis is based on the public Twitter US Airline Sentiment dataset.

---

## Goals
- Classify tweets into positive, neutral, or negative sentiment
- Identify key text features that drive negative vs. positive sentiment
- Produce interpretable results to support customer service insights

---

## Methodology

### 1) Data Preprocessing
- Removed HTML/markup and expanded contractions
- Lowercased text, tokenized, and removed stopwords
- Applied stemming and/or lemmatization
- Generated exploratory visuals (e.g., word clouds)

### 2) Feature Engineering
- Text vectorization with Bag-of-Words (CountVectorizer)
- TF-IDF representations for richer weighting

### 3) Modeling and Evaluation
- Baseline and final model: Random Forest classifier
- Train/test split and cross-validation
- Evaluation metrics: accuracy, precision, recall, F1-score, and confusion matrix

---

## Repository Structure
```
AIML-Twitter-US-Airline-Sentiment/
├── Twitter US Airline Sentiment Project.ipynb # Main notebook
├── Twitter US Airline Sentiment Project.html # Exported notebook
├── Tweets.csv # Dataset (Twitter US Airline Sentiment)
└── README.md # Project documentation
```

---

## Dataset Notes
- Source: Twitter US Airline Sentiment
- Included file: `Tweets.csv`

---

## Results
- Random Forest with TF-IDF features achieved strong performance on the hold-out set
- Include your final metrics here (e.g., Accuracy, Macro F1)


## Results
- Random Forest with TF-IDF features achieved strong performance on the hold-out set
- Include your final metrics here (e.g., Accuracy, Macro F1)
