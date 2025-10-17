# Email Spam Detector

**Email Spam Detector** is a machine learning / NLP project that detects whether an email is spam or not. The repo contains data preprocessing, feature engineering, model training, evaluation, and inference code — ready to run locally and easy to extend.

## 🔍 Project Overview
This project builds a classifier that labels email messages as **spam** or **ham (not spam)** using classical ML (e.g., Logistic Regression, SVM, RandomForest) and optionally a simple neural approach. It includes data cleaning, vectorization (TF-IDF), model training, evaluation metrics, and a prediction script for single emails or batch files.

## ✅ Features
- Text cleaning and normalization (lowercasing, punctuation removal, stopword removal, optional stemming/lemmatization)
- Tokenization and TF-IDF feature extraction
- Multiple model options (Logistic Regression, SVM, RandomForest, simple neural network)
- Train / evaluate / save / load model pipeline
- CLI and script for predicting single emails or batch CSV files
- Simple web API example (Flask) for inference (optional)
- Jupyter notebooks for EDA & experiments

## 🧰 Tech stack
- Python 3.8+
- scikit-learn, pandas, numpy
- nltk / spacy (text processing) — optional
- joblib or pickle (model serialization)
- Flask or FastAPI (optional inference API)
- jupyter (exploration)

## 📁 Repository structure (suggested)
