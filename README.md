# 📧 SMS Spam Detection using Various NLP Techniques 🚀

## Overview

Hey there! 👋 This project is my playground for practicing different Natural Language Processing (NLP) techniques to detect spam messages. Here's what I've been experimenting with:

- 🧠 **Bag of Words (BoW)**
- 📊 **Term Frequency-Inverse Document Frequency (TF-IDF)**
- 🔍 **Word2Vec (Average Word2Vec)**

Hope it helps you too if you're diving into NLP and spam detection! 🌟

## Dataset 📂

The dataset used is the **"SMSSpamCollection"** which consists of SMS messages labeled as 'spam' or 'ham' (not spam). The dataset is loaded and processed as a pandas DataFrame.

## Preprocessing Steps 🔧

1. **Text Cleaning**: Removal of non-alphabetic characters and conversion to lowercase.
2. **Tokenization**: Splitting text into words.
3. **Stopword Removal**: Removing common English words that do not contribute to the meaning.
4. **Stemming**: Reducing words to their root form.
5. **Lemmatization**: Reducing words to their base or dictionary form.

## Feature Extraction Techniques 💡

### Bag of Words (BoW) 📚

The BoW model is implemented using `CountVectorizer` with bigrams and binary features. The model is then evaluated using a Multinomial Naive Bayes classifier.

### TF-IDF 📈

The TF-IDF model is implemented using `TfidfVectorizer` with bigrams and binary features. The model is evaluated using both Multinomial Naive Bayes and Random Forest classifiers.

### Word2Vec 🧩

Word2Vec embeddings are generated using the `gensim` library. The average Word2Vec vector for each message is used as a feature, and the model is evaluated using a Random Forest classifier.

## Model Evaluation 🏆

The performance of each model is evaluated using the following metrics:
- 🎯 **Precision**
- 🕵️ **Recall**
- ⚖️ **F1-Score**
- 📏 **Accuracy**

## Results 📝

The results for each model are printed using a classification report which provides a detailed analysis of the model's performance. 📊

## Getting Started 🚀

### Prerequisites 🛠️

- Jupyter Notebook
- Required Python packages: `pandas`, `nltk`, `gensim`, `numpy`, `tqdm`, `sklearn`

### Installation 📥

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sms-spam-detection-nlp.git
   cd sms-spam-detection-nlp
