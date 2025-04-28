# Disaster Tweets Classification - Kaggle Competition

## Overview
This project was completed as part of a Master's level course on Deep Learning and Natural Language Processing (NLP).

The objective was to classify tweets as related to real disasters (1) or not (0) using a combination of traditional machine learning and deep learning models.

We participated in the Kaggle competition: [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started).

## Deliverables
- **Jupyter Notebook**: Contains data analysis, model building, training, evaluation, and conclusions.
- **GitHub Repository**: Includes code, README, and final submission file.
- **Kaggle Submission Screenshot**: Shows leaderboard score for the best model.

## Models Built
- **Logistic Regression with TF-IDF features** (Baseline)
- **LSTM model** (Deep learning with tuned hyperparameters)
- **GRU model** (Alternative deep learning architecture)

## Highlights
- Achieved a validation accuracy of approximately **80%** across different models.
- Performed extensive hyperparameter tuning on the LSTM model (embedding dimension, dropout rate, batch size, vocabulary size).
- Explored the use of EarlyStopping to mitigate overfitting.
- Visualized model comparisons with validation accuracy graphs and training loss curves.

## How to Reproduce
1. Download the dataset from the Kaggle competition: [NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started).
2. Place the CSV files (`train.csv`, `test.csv`, `sample_submission.csv`) in the working directory.
3. Run the Jupyter Notebook step-by-step:
    - Data loading
    - Exploratory Data Analysis (EDA)
    - Preprocessing and Text Cleaning
    - Feature Extraction (TF-IDF or Tokenization)
    - Model Training (Logistic Regression, LSTM, GRU)
    - Evaluation
    - Prediction on the test set
    - Generate `submission.csv` for Kaggle
