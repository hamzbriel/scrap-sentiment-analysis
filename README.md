# Sentiment Analysis

This project performs sentiment analysis on text data. Scraping from stardew valley steam games reviews and preprocessing the text data to train a sentiment classification model.

## Features
- Data collection and scraping
- Text preprocessing
- Sentiment classification
- Model training and evaluation

## Files
- `scraping.ipynb`: Jupyter notebook for scraping text data.
- `training.ipynb`: Jupyter notebook for training the sentiment analysis model.
- `dataset_raw.csv`: Raw dataset collected from scraping.
- `dataset.csv`: Labelled dataset ready for model training.
- `requirements.txt`: List of required Python packages.
- `outputs/results/`: Directory containing model evaluation results.

## Experiment Results
| Experiment | Train Accuracy | Test Accuracy | Test Macro F1 | Test Weighted F1 | Training Seconds |
| :--- | :---: | :---: | :---: | :---: | :---: |
| TF-IDF + Logistic Regression | 0.9713 | 0.8625 | 0.8405 | 0.8636 | 8.62 |
| Embedding + BiLSTM | 0.9206 | 0.8421 | 0.8182 | 0.8461 | 421.03 |
| TF-IDF + MLP Neural Network | 0.9734 | 0.8425 | 0.8150 | 0.8408 | 44.06 |
