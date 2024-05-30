# 📧 SMS Spam Detection using Various NLP Techniques 

## Overview

Hey there! This project is my playground for practicing different Natural Language Processing (NLP) techniques to detect spam messages. Here's what I've been experimenting with:

- 🧠 Bag of Words (BoW)
- 📊 Term Frequency-Inverse Document Frequency (TF-IDF)
- 🔍 Word2Vec (Average Word2Vec)

Hope it helps you too if you're diving into NLP and spam detection!

## Techniques and Models

1. **Bag of Words (BoW)**
   - Uses CountVectorizer to create a BoW model.
   - Applied a Multinomial Naive Bayes classifier.

2. **Term Frequency-Inverse Document Frequency (TF-IDF)**
   - Uses TfidfVectorizer to create a TF-IDF model.
   - Applied both Multinomial Naive Bayes and Random Forest classifiers.

3. **Word2Vec**
   - Trained a Word2Vec model from scratch.
   - Used an average Word2Vec approach.
   - Applied a Random Forest classifier.

## Notebook Structure

1. **Setup and Data Loading**
   - Installing required packages and loading the dataset.

2. **Data Cleaning & Preprocessing**
   - Cleaning and preprocessing the data by removing non-alphabetic characters, converting text to lowercase, and removing stopwords. Also did some stemming.

3. **Bag of Words Model**
   - Creating a BoW model and checking its performance with a Multinomial Naive Bayes classifier.

4. **TF-IDF Model**
   - Creating a TF-IDF model and evaluating it using both a Multinomial Naive Bayes classifier and a Random Forest classifier.

5. **Word2Vec Model**
   - Creating a Word2Vec model from scratch, applying average Word2Vec to each document, and checking the results with a Random Forest classifier.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages: `pandas`, `nltk`, `gensim`, `numpy`, `tqdm`, `sklearn`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sms-spam-detection-nlp.git
   cd sms-spam-detection-nlp
