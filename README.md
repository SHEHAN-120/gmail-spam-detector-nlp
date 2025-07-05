# Gmail Spam Detector Using NLP (Bag of Words + Naive Bayes)

This project is a simple but effective spam detection system built using Natural Language Processing (NLP) techniques. It classifies Gmail messages as spam (1) or not spam (0) using a Bag of Words model and a Multinomial Naive Bayes classifier.

## 📌 Project Overview

Spam detection is a classic NLP problem that involves text classification. This project demonstrates how to:

- Preprocess text data using Python
- Convert raw text into numerical features using Bag of Words
- Train a Naive Bayes classifier to identify spam
- Evaluate model performance using metrics 

## 🧰 Tools & Libraries Used

- Python (Google Colab)
- `pandas`, `numpy`
- `scikit-learn`
  - `CountVectorizer` for Bag of Words
  - `MultinomialNB` for classification
  - `train_test_split` for splitting data
  - `classification_report` for performance metrics

## 📊 NLP Techniques Used

- **Bag of Words (BoW):** Used to convert email text into numerical format.
- **Multinomial Naive Bayes:** A common and efficient algorithm for text classification.
- **Basic text preprocessing:** Handled through CountVectorizer’s built-in tokenizer and cleaner.

## 🧪 How It Works

1. Load and clean the email dataset.
2. Use `CountVectorizer` to extract word frequency features.
3. Split the data into training and testing sets.
4. Train a `MultinomialNB` model.
5. Make predictions and evaluate the classifier.

## 🚀 Results

The model achieved strong performance on the test set, making it a practical solution for spam filtering tasks.

# Sample Spam


![Screenshot (4265)_LI](https://github.com/user-attachments/assets/063d51a7-28a4-4bfd-ace5-b95e5c8efa86)
