# 📧 Email Spam Detection using Machine Learning & NLP

## 📌 Project Overview

Spam emails are one of the most common problems in digital communication. These emails often contain unwanted advertisements, scams, phishing links, or malicious content.

In this project, I built an **Email Spam Detection System using Machine Learning** that classifies messages into two categories:

- ✅ Ham (Non-Spam)
- 🚫 Spam

The model learns from previous email messages and predicts whether a new message is spam or not using **Natural Language Processing (NLP)** techniques.

---

## 🎯 Objective

To develop a machine learning model that can automatically detect and classify spam emails/messages with high accuracy.

---

## 📂 Dataset

The dataset contains two columns:

| Column | Description |
|--------|-------------|
| v1 | Email category (ham/spam) |
| v2 | Email/message text |

Labels:

- Ham → Normal message
- Spam → Spam message

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

---

## 🔍 Project Workflow

### 1. Data Collection
Loaded the email dataset containing spam and ham messages.

### 2. Data Cleaning

Performed:
- Removed duplicate records
- Handled unnecessary characters
- Converted text into lowercase

### 3. Exploratory Data Analysis

Analyzed:
- Spam vs Ham distribution
- Dataset patterns

### 4. Text Preprocessing

Applied NLP techniques:

- Text cleaning
- Stop word removal
- TF-IDF Vectorization

### 5. Model Training

Machine Learning Algorithm used:

**Multinomial Naive Bayes Classifier**

Why Naive Bayes?

It performs effectively for text classification tasks like spam detection because it handles word frequency-based features efficiently.

### 6. Model Evaluation

Evaluated the model using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Model Performance

The model achieved high accuracy in classifying spam and non-spam messages.

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-score

---
