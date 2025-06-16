# Sentiment-Analysis-using-Deep-Leaning

This project performs sentiment classification on customer reviews using multiple deep learning models including CNN, RNN, LSTM, and GRU. It focuses on understanding public sentiment through natural language processing and evaluating model effectiveness on real-world review data.

Objective
To build models that can classify text reviews into 5 categories very positive, positive, neutral, negative, or very negative using sequential neural networks, and to compare their performance.

Key Features
- Sentiment classification using CNN, RNN, LSTM, and GRU architectures
- Preprocessing pipeline including stopword removal, tokenization, and padding
- Comparative analysis of model performance
- Model evaluation using accuracy, loss, and confusion matrix
- Visualization of training/validation performance

Dataset
- Source: Publicly available dataset sentiment analysis on company reviews from kaggle
- Classes: very positive, positive, neutral, negative, or very negative
- Preprocessing:
  - Text cleaning and lowercasing
  - Stopword and punctuation removal
  - Tokenization with Keras tokenizer
  - Sequence padding for uniform input length
