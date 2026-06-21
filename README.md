# Arabic Emotion Detection using Traditional NLP and LLMs

This project focuses on Arabic sentiment classification using both traditional machine learning techniques and Large Language Model (LLM)-based approaches.

## Overview
The goal of this project is to classify Arabic tweets into two sentiment classes:
- Positive
- Negative

The project compares traditional NLP pipelines with prompt-based LLM classification.

## Dataset
- Original dataset: 10,065 Arabic tweets
- Final cleaned dataset: 7,469 tweets
- Labels reduced into:
  - Positive
  - Negative

## Traditional NLP Pipeline
### Preprocessing
- Remove missing values
- Arabic normalization
- Remove punctuation
- Remove emojis
- Remove stopwords
- Tokenization
- Lemmatization

### Feature Engineering
- Bag of Words (BoW)
- N-grams
- TF-IDF
- Feature Selection

### Models
- Logistic Regression
- Random Forest
- SVM

## LLM-Based Approach
Used ALLaM with:
- Zero-shot prompting
- One-shot prompting
- Few-shot prompting

## Results
### Best Traditional Model
TF-IDF + SVM
- Accuracy: 84.92%
- F1-score: 84.89%

### Best LLM Model
One-shot prompting with ALLaM
- Accuracy: 85%
- F1-score: 86%

## Team Members
- Shumukh Eid Altoom
- Bushra Abdulrahman Almutrafi
- Layal Mohammed Alhazmi

## Tools
Python, Scikit-learn, NLTK, CAMeL Tools, Google Colab
