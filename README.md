# Finetuned DistilBERT for Sentiment Analysis

This project involves fine-tuning a DistilBERT model for the task of sentiment analysis. The objective is to classify text into five categories of sentiment: very negative, negative, neutral, positive, and very positive. We utilize the `SetFit/sst5` dataset for training and evaluation purposes.

## Contents

- **Loading Data and Libraries**: Initial setup includes loading the necessary libraries and the dataset.
- **Model and Dataset**: We fine-tune the Distilbert model, specifically designed for sentiment analysis with five labels, using the `SetFit/sst5` dataset.
  - Labels interpretation in the `sst5` dataset:
    - `0`: Very Negative
    - `1`: Negative
    - `2`: Neutral
    - `3`: Positive
    - `4`: Very Positive
- **Hyperparameter Tuning**: Details on selecting the optimal hyperparameters for model training.
- **Model Selection**: The model with a learning rate of 5e-05, trained over 3 epochs, is chosen based on its performance.
- **Performance Evaluation**: f1-score is used for evaluation.
