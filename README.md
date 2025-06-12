# 📰 Indonesian News Classification Using Machine Learning

This repository contains the source code, dataset references, and experimental results for the project **"Indonesian News Classification Using Machine Learning Algorithms."** The objective is to classify Indonesian-language news articles into categories (e.g., politics, sports, entertainment) or detect whether they are **hoax** or **authentic**.

## 📌 Project Overview

With the increasing amount of digital news content in Indonesia—along with the growing spread of misinformation—automated classification is essential. This project leverages natural language processing (NLP) and machine learning techniques to classify news based on textual content.

The classification task will be:
- **Binary**: Classifying news as **Hoax** vs. **Non-Hoax**

## 📊 Dataset

- **Source**: [Kaggle](https://www.kaggle.com/) and/or public Indonesian news datasets  

- **Features**:
  - News Title
  - News Body
  - Label (e.g., category name or hoax/non-hoax)

- **Size**: ~XXXX articles *(update based on actual dataset)*

## ⚙️ Methodology

1. **Text Preprocessing**
   - Lowercasing
   - Tokenization
   - Stopword removal (Bahasa Indonesia)
   - Stemming using [Sastrawi](https://github.com/har07/PySastrawi)
   - TF-IDF vectorization

2. **Machine Learning Models**
   - Logistic Regression
   - Random Forest
   - Multinomial Naive Bayes
   - (Optional) Deep Learning models (e.g., LSTM or IndoBERT)

3. **Evaluation Metrics**
   - Accuracy
   - Precision, Recall, F1-Score
   - Confusion Matrix
   - K-Fold Cross Validation
