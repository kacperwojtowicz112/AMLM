# Sentiment Analysis Models

This repository contains code and data for comparing two sentiment analysis models: one using FastText embeddings and another using an LSTM network.

## Contents

- `file.csv`: Dataset containing tweets and their sentiment labels.
- `Project.ipynb`: Jupyter notebook with code for preprocessing, training, and evaluating the models.

## Models

### FastText Model

- Utilizes pre-trained FastText embeddings for word representation.
- Captures semantic relationships between words.
- Implemented using PyTorch.

### LSTM Model

- Uses an LSTM network to process sequences of word embeddings.
- Learns word embeddings during training.
- Implemented using PyTorch.

## Analysis

The notebook includes detailed analysis of the models' performance. Key points include:

- Accuracy: The overall accuracy of both models on the validation set.
- Confusion Matrix: Visualization of the confusion matrix to understand misclassifications.
- Loss Curves: Plots of training and validation loss over epochs to monitor overfitting.

## Key Findings

- The FastText model benefits from pre-trained embeddings, which can lead to better generalization, especially with smaller datasets.
- The LSTM model, while more flexible, may require more data and careful tuning to achieve comparable performance.

## Conclusion
Both models have their strengths and can be chosen based on the specific requirements of the task. The FastText model is advantageous for leveraging pre-trained embeddings, while the LSTM model provides a robust framework for learning representations from scratch.