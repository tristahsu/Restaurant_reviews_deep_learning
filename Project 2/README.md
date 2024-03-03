
## Project 2: Sentiment Classification with Machine Learning Approaches (LA2)
## Overview
This project focuses on the application of various machine learning models to classify the sentiment of restaurant reviews. By analyzing textual feedback from customers, the project aims to automatically determine whether a review is positive or negative, providing valuable insights into customer satisfaction and areas for improvement.

## Objectives
- To compare the effectiveness of different machine learning models in sentiment classification.
- To explore feature extraction techniques that best capture the sentiment expressed in text.
- To enhance the understanding of how preprocessing steps impact model performance.
## Methodology
The project employs a variety of machine learning models, including Naive Bayes, Support Vector Machines (SVM), and Logistic Regression, to classify sentiments. It also investigates different feature extraction methods, such as bag-of-words and TF-IDF, to prepare the text data for modeling.

## Steps Included
- Data Preprocessing: Cleaning text data and preparing it for analysis.
- Feature Extraction: Transforming text into numerical features suitable for machine learning models.
- Model Training and Evaluation: Applying different models to the processed data and evaluating their performance in sentiment classification.
## Data Source
The sentiment classification is performed on a dataset containing restaurant reviews. Each review in the dataset is labeled with a sentiment (positive or negative), facilitating the training and evaluation of models.

## Findings
The project's findings highlight the relative strengths and weaknesses of different machine learning models and feature extraction techniques in sentiment classification. It provides insights into which combinations of methods yield the most accurate predictions of sentiment.
## Conclusion
Naive Bayes with Count Vectorizer:

Accuracy: 0.92

SVM with Count Vectorizer:

Accuracy: 0.95 (0.946)

Naive Bayes with TF-IDF:

Accuracy: 0.91

SVM with TF-IDF:

Accuracy: 0.95(0.949)

VaderSentiment:

Accuracy: 0.86

My observation is that Machine learning models, especially SVM with TF-IDF, outperform lexicon-based approach. SVM models, whether with Count Vectorizer or TF-IDF, consistently show high accuracy, indicating their effectiveness. Naive Bayes models perform well but may slightly lag behind SVM in capturing complex sentiments. VaderSentiment, being lexicon-based, resulting in lower accuracy.
In conclusion, for better accuracy and nuanced sentiment analysis, machine learning models, particularly SVM with TF-IDF, are preferred over lexicon-based approaches like VaderSentiment.
