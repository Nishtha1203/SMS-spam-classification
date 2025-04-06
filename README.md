# SMS-spam-classification

This project implements a complete pipeline for detecting spam messages in SMS data using Natural Language Processing (NLP) and machine learning models. It includes data preprocessing, feature extraction using TF-IDF, and classification using three different models—Naive Bayes, Support Vector Machine (SVM), and Logistic Regression. The dataset used is the well-known "SMS Spam Collection."

#### Key steps in the project:
1.  Data Preprocessing:
-  Text cleaning (removing email addresses, URLs, numbers, etc.).
-  Tokenization, stemming, and stopword removal.
2.  Feature Extraction:
-  TF-IDF Vectorization to convert text into numerical features.
3.  Model Training and Evaluation:
-  Training models: Naive Bayes, SVM, and Logistic Regression.
-  Evaluation using accuracy score, precision, recall, F1-score, and confusion matrix.
4.  Visualization:
-  Bar chart for class distribution.
-  Wordcloud for most frequent words in spam and ham messages.

#### Model Accuracy:
-  Naive Bayes: 98.0%
-  SVM: 98.4%
-  Logistic Regression: 97.2%

#### Dataset:
-  Source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection 
-  Format: Tab-separated values (\t)
-  Classes: ham, spam

