## Project 4: Text Classification with Deep Learning - Part 1 (LA4)
## Overview
This project introduces text classification using deep learning techniques, focusing on the use of Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks. It aims to classify restaurant reviews into predefined categories, enhancing the understanding of customer feedback on a granular level.

## Objectives
- To explore the application of RNNs and LSTMs in text classification.
- To demonstrate the preprocessing required for deep learning models.
- To evaluate the performance of deep learning models in classifying text data.
## Methodology
The project follows a structured approach to text classification using deep learning:
- Data Preprocessing: Includes tokenization, sequencing, and padding of text data to prepare it for input into deep learning models.
- Model Building: Construction of RNN and LSTM models using TensorFlow and Keras, setting up the architecture for text classification.
- Training and Evaluation: Training the models on a dataset of restaurant reviews and evaluating their performance in accurately classifying the reviews.
## Data Source
The dataset comprises a collection of restaurant reviews, categorized by sentiment or specific aspects of the dining experience, such as food quality, service, or ambiance. This dataset serves as the basis for training and testing the deep learning models.

## Findings
The project's findings highlight the effectiveness of RNN and LSTM models in handling sequence data like text, showing promising results in classifying restaurant reviews. It also discusses the challenges encountered, such as overfitting and the choice of hyperparameters, and potential solutions to these issues.
## Conclusion
GRU with Pre-trained GloVe Embeddings:

Test Accuracy: 94.26%

Parameters: 3,430,449 (88,449 trainable)

Stable increase in training and validation accuracy over epochs.

LSTM with Pre-trained GloVe Embeddings:

Test Accuracy: 93.41%

Parameters: 3,459,377 (117,377 trainable)

Similar performance to GRU with pre-trained embeddings.

GRU with Trainable Embeddings:

Test Accuracy: 93.74%

Parameters: 3,430,449 (all trainable)

Slightly fluctuating validation accuracy during training.

LSTM with Trainable Embeddings:

Test Accuracy: 93.74%

Parameters: 3,459,377 (all trainable)

Similar performance to GRU with trainable embeddings.

SVM with TF-IDF:

Accuracy: 95.86%

Outperformed deep learning models in accuracy.

Comments:

Pre-trained embeddings provided a good start.

No significant difference between GRU and LSTM.

SVM with TF-IDF outperformed deep learning models in accuracy.

Consider computational resources and dataset characteristics when choosing models.
