# 📧 Email/SMS Spam Detection with Machine Learning

## 📌 Project Overview

This project implements a Natural Language Processing (NLP) and Machine Learning-based spam detection system that classifies text messages into two categories: **Spam** or **Ham (Legitimate)**.

The project uses text preprocessing, TF-IDF feature extraction, and two machine learning classifiers: **Multinomial Naive Bayes** and **Logistic Regression**.

## 🎯 Objectives

* Load and explore a spam/ham text dataset
* Analyze spam and ham class distribution
* Clean and preprocess text data
* Convert text into numerical features using TF-IDF
* Train multiple machine learning classifiers
* Evaluate model performance
* Visualize confusion matrices
* Identify important words using WordClouds
* Test the trained model on new messages

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn
* WordCloud
* Google Colab / Jupyter Notebook

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset**, containing messages labeled as:

* `ham` — legitimate message
* `spam` — spam message

Dataset source:

**Kaggle:** SMS Spam Collection Dataset

https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Class Distribution Analysis
   ↓
Text Preprocessing
   ↓
TF-IDF Feature Extraction
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Naive Bayes + Logistic Regression
   ↓
Model Evaluation
   ↓
Spam/Ham Prediction
```

## 🧹 Text Preprocessing

The text preprocessing pipeline includes:

1. Converting text to lowercase
2. Removing punctuation and special characters
3. Removing stopwords
4. Removing unnecessary whitespace

## 🔢 TF-IDF Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) converts text into numerical features that machine learning algorithms can process.

It assigns greater importance to words that are useful for distinguishing individual messages while reducing the importance of word
