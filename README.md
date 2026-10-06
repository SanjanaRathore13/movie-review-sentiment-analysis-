# Movie Review Sentiment Analysis

## Overview

This project performs sentiment analysis on movie reviews using Natural Language Processing (NLP) and Machine Learning.

The IMDb Movie Reviews dataset is used to classify reviews as either **Positive** or **Negative**.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## NLP Techniques

- Text Preprocessing
- HTML Tag Removal
- Punctuation Removal
- Tokenization
- Stopword Removal
- Stemming
- Lemmatization
- Bag of Words
- N-grams
- TF-IDF

## Machine Learning Models

Three machine learning models were implemented and compared:

- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 89.96% |
| Naive Bayes | ~88% |
| SVM | 90.95% |

SVM achieved the highest accuracy among the tested models.

## Prediction

The trained SVM model can also predict the sentiment of a new movie review.

Example:

```text
Input: This movie was absolutely amazing and worth watching.

Output: Positive
