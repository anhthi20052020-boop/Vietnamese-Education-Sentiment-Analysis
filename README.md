# Vietnamese Education Sentiment Analysis

## Overview
This project builds an Aspect-Based Sentiment Analysis (ABSA) system for Vietnamese educational feedback using PhoBERT.

## Models
- TF-IDF + Logistic Regression
- TF-IDF + XGBoost
- PhoBERT Fine-tuning

## Features
- Vietnamese NLP preprocessing
- Aspect extraction
- Sentiment classification
- Streamlit dashboard

## Dataset
- UIT-VSFC
- Collected EdTech feedback

## Results

| Model | Accuracy | F1-Macro |
|---|---|---|
| Logistic Regression | 0.8830 | 0.8773 |
| XGBoost | 0.9017 | 0.8969 |
| PhoBERT | 0.9550 | 0.9530 |

## Technologies
- Python
- PyTorch
- Transformers
- Scikit-learn
- Streamlit

## Authors
- Nguyen Hoang Anh Thi
- Nguyen Ngoc Anh Thu
