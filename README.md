# BERT_MovieReviews


## Project Overview
The goal of this project is to implement a natural language processing (NLP) model that automatically classifies movie reviews as positive or negative based on the review text.


## Dataset
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data

Each sample contains:

review: movie review text

sentiment: sentiment label (positive / negative)

The sentiment labels were converted into numerical form for training:

positive → 1

negative → 0

## Model

Model: bert-base-uncased

Framework: PyTorch

Library: Hugging Face Transformers

Task: Binary Text Classification (Sentiment Analysis)
