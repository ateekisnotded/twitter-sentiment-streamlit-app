# twitter-sentiment-streamlit-app
NLP sentiment analysis model trained on Twitter data, with a Streamlit app built for interactive, real-time sentiment prediction.
# Twitter Sentiment Analysis — NLP Model with Streamlit App

## Overview
This project builds an NLP sentiment analysis model trained on Twitter data
to classify tweets by sentiment (Negative / Neutral / Positive), along with
a Streamlit application built to serve the model for interactive, real-time
predictions.

## Dataset
Twitter dataset — labeled tweets used to train a sentiment classification model.

## Approach
- Text preprocessing: tokenization, cleaning, and normalization of tweet text
- Built and trained an NLP/deep learning model for sentiment classification
- Saved the trained model (`sentiment_model.h5`) and tokenizer
  (`tokenizer.joblib`) for reuse without retraining
- Built a Streamlit app (`twitter_sentiment_app.py`) to serve the model
  for interactive, real-time sentiment prediction

## Evaluation
Achieved 70% accuracy on the test set, with a weighted F1-score of 0.70
across all three sentiment classes (Negative, Neutral, Positive).

| Class    | Precision | Recall | F1-score |
|----------|-----------|--------|----------|
| Negative | 0.70      | 0.66   | 0.68     |
| Neutral  | 0.68      | 0.64   | 0.66     |
| Positive | 0.72      | 0.81   | 0.76     |

## Files
- `twitter_sentiment_main.py` — model training and evaluation
- `twitter_sentiment_app.py` — Streamlit app for serving predictions
- `sentiment_model.h5` — saved trained model
- `tokenizer.joblib` — saved tokenizer for text preprocessing
- `Twitter_Data.csv` — dataset used

## Tools & Libraries
Python, Streamlit, TensorFlow/Keras, Scikit-learn, Jupyter Notebook, Spyder

## Key Takeaway
Beyond model training, this project covers the deployment-readiness step —
saving a trained model and tokenizer, then building a usable Streamlit
interface to serve predictions.
