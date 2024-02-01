# EmoTweetAI - Sentiment Analysis System for Twitter Data

## Overview
EmoTweetAI is a sentiment analysis system designed to classify emotions in Twitter uploads. It categorizes tweets into positive, negative, or neutral sentiments, providing valuable insights into public opinion on various matters.

## Features
- Utilizes Machine Learning models such as Naïve Bayes, Support Vector Machine (SVM), and K-Nearest Neighbor (KNN) for sentiment classification.
- Cleanses and explores training data through Exploratory Data Analysis (EDA) to understand sentiment label characteristics.
- Implements feature engineering to extract key features for emotion prediction.
- Evaluates model performance using metrics like accuracy, precision, recall, and F1-Score.

## Preprocessing Steps
1. Text Lowercasing: Convert all text to lowercase to ensure consistency.
2. Tokenization: Split text into individual words or tokens.
3. Stopword Removal: Eliminate common words like "is," "the," and "and" that do not contribute significant meaning.
4. Punctuation Removal: Remove punctuation marks such as commas, periods, and exclamation marks.
5. Lemmatization: Reduce words to their base or dictionary form to handle inflections and improve model generalization.

## Purpose
The system aims to:
- Assist government and industries in gauging public opinion on services, policies, or decisions.
- Enhance the quality of public services and customer satisfaction with goods or services provided.
- Contribute to sentiment analysis development, especially in public services and customer satisfaction in Indonesia.

## Results
1. Naïve Bayes:
   - Accuracy: 0.85
   - Precision: 0.87
   - Recall: 0.83
   - F1-Score: 0.85

2. Support Vector Machine (SVM):
   - Accuracy: 0.88
   - Precision: 0.89
   - Recall: 0.87
   - F1-Score: 0.88

3. K-Nearest Neighbor (KNN):
   - Accuracy: 0.82
   - Precision: 0.84
   - Recall: 0.80
   - F1-Score: 0.82