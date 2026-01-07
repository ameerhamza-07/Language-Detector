# Language Detection Using Machine Learning

This project predicts the language of a given text using Machine Learning.
It uses the Multinomial Naive Bayes algorithm along with CountVectorizer
to classify text into different languages.

## Problem Statement
Language detection is an important task in Natural Language Processing.
This project identifies the language of a user-input text based on trained data.

## Dataset
- File: language.csv
- Columns:
  - Text: Sentence or phrase
  - language: Language label

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- CountVectorizer
- Naive Bayes

##  Workflow
1. Load dataset
2. Convert text to numerical form using CountVectorizer
3. Split data into training and testing sets
4. Train model using Multinomial Naive Bayes
5. Evaluate accuracy
6. Predict language for user input text

## Model Used
- Multinomial Naive Bayes

## ✅ Accuracy
The model achieves good accuracy on the test dataset.
