# Sentiment Analysis of Movie Reviews using Machine Learning

## Project Overview

This project performs Sentiment Analysis on movie reviews using Natural Language Processing (NLP) and Machine Learning. The model classifies reviews as either **Positive** or **Negative** based on the text provided by the user.

## Features

* Text preprocessing and cleaning
* Tokenization and lemmatization
* TF-IDF Vectorization
* Machine Learning classification
* Predicts sentiment of custom reviews
* Data visualization using Matplotlib
* Word Cloud generation

## Dataset

The project uses a movie review dataset containing review texts and their corresponding sentiment labels.

Dataset columns:

* `review` : Movie review text
* `sentiment` : Positive (1) or Negative (0)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* WordCloud

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Feature Extraction
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Sentiment Prediction
9. Data Visualization

## Model Used

* Logistic Regression / Naive Bayes (depending on implementation)

## Results

The model successfully predicts whether a movie review is positive or negative based on the input text.

Example:

Input:
"This movie was amazing and the acting was excellent."

Output:
Positive 😊

Input:
"The film was boring and a complete waste of time."

Output:
Negative 😔

## Installation

```bash
pip install pandas numpy scikit-learn nltk matplotlib wordcloud
```

## Run the Project

```bash
python sentiment_analysis.py
```

## Future Improvements

* Multi-class sentiment analysis
* Deep Learning models (LSTM, BERT)
* Web application deployment using Streamlit or Flask
* Real-time sentiment analysis

## Author

Sayan Bera

B.Tech CSE (AI & ML)
KIIT University

