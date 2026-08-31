# Movie Review Sentiment Analysis

A machine learning project that classifies movie reviews as positive or negative using traditional NLP techniques.

## Project Overview

This project explores different text vectorization techniques and machine learning algorithms for sentiment classification.

### Techniques Used

- Text preprocessing
- Bag of Words (BoW)
- TF-IDF
- Logistic Regression
- Multinomial Naive Bayes

## Dataset

IMDb 50K Movie Review Dataset.

The dataset contains 50,000 movie reviews labeled as either positive or negative.

## NLP Pipeline

Review
↓
Text Cleaning
↓
Train/Test Split
↓
Text Vectorization
↓
Machine Learning Model
↓
Sentiment Prediction

## Models & Results

| Vectorization | Model | Accuracy |
|---|---|---:|
| Bag of Words | Logistic Regression | 89.00% |
| Bag of Words | Multinomial Naive Bayes | 86.00% |
| TF-IDF | Multinomial Naive Bayes | 86.88% |
| TF-IDF | Logistic Regression | 89.58% |

## Best Model

TF-IDF + Logistic Regression achieved the best accuracy of approximately **89.58%**.

## Example

Input:

"This movie was absolutely amazing. The acting was brilliant."

Prediction:

Positive

## Future Improvements

- Try Linear SVM
- Experiment with n-grams
- Hyperparameter tuning
- Try word embeddings
- Build a web application using Streamlit
