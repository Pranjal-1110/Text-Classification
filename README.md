# Text Classification with Naive Bayes

This repository contains the implementation and analysis of text classification using Naive Bayes classifiers, comparing a custom implementation with sklearn's MultinomialNB on a dataset processed using NLTK and sklearn.

## Project Overview

- Utilized NLTK and sklearn to fetch data, tokenize text, and remove over 800 stop words and punctuation marks.
- Developed an algorithm to build a vocabulary and selected 10,000 out of 113,000 words for classification.
- Implemented a function to convert text data into a 2D matrix, processing 11,314 documents and 10,000 features.
- Designed a Naive Bayes classifier from scratch, achieving 88% accuracy compared to 89% with MultinomialNB from sklearn.
- Conducted frequency distribution analysis using Matplotlib to refine feature selection from the top 50,000 words.

## Project Details

### Data Processing

- **NLTK and sklearn**: Used for data fetching, text tokenization, and removal of stop words and punctuation.
- **Vocabulary Building**: Developed an algorithm to create a vocabulary and selected 10,000 most frequent words for classification.

### Naive Bayes Implementation

- **Custom Naive Bayes Classifier**: Implemented from scratch to classify text documents based on word frequencies.
- **MultinomialNB Comparison**: Benchmarking custom implementation against sklearn's MultinomialNB classifier.

### Feature Selection

- **Frequency Distribution Analysis**: Used Matplotlib to analyze and select top features (words) for classification.


