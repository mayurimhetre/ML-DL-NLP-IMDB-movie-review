# 🎬 IMDB Movie Review Sentiment Analysis

## 📖 Overview
This project focuses on **sentiment analysis** using the **IMDB Movie Review Dataset**, a popular benchmark dataset in Natural Language Processing (NLP).  
The goal is to classify movie reviews as **positive** or **negative** based on the text content.

Sentiment analysis is a real-world application of NLP and machine learning that helps understand opinions, emotions, and attitudes expressed in textual data.

---

## 📂 Dataset Description
The IMDB Movie Review Dataset contains **50,000 movie reviews** collected from the Internet Movie Database (IMDB).

### Key Features:
- **Total Reviews:** 50,000
- **Positive Reviews:** 25,000
- **Negative Reviews:** 25,000
- **Balanced Dataset:** Equal number of positive and negative samples
- **Labels:**
  - `1` → Positive sentiment
  - `0` → Negative sentiment

Each review is a piece of raw text expressing the reviewer’s opinion about a movie.

---

## 🎯 Project Objective
The primary objective of this project is to **build a machine learning or deep learning model** that can automatically determine the sentiment of a movie review.

This project helps users understand:
- Text preprocessing techniques
- Feature extraction from text data
- Sentiment classification
- Model evaluation and performance analysis

---

## 🛠️ What Is Done in This Project
The project follows these main steps:

1. **Load the Dataset**
2. **Text Preprocessing**
   - Lowercasing text
   - Removing punctuation and special characters
   - Removing stopwords
   - Tokenization
3. **Feature Extraction**
   - Bag of Words (BoW)
   - TF-IDF
   - Word Embeddings (optional)
4. **Model Building**
   - Traditional ML models (Random forest, Multinomial NB)
   - Deep Learning models (LSTM)
5. **Model Evaluation**
   - Accuracy
---

## Results

**1.Multinomial NB:**

accuracy: 0.8432

**2.Random forest classifier:**

accuracy: 0.84

**3. MNB with TFIDF :**

accuracy: 0.85

4.alpha=1.0 gives accuracy: 0.85
 
**5. Deep Neural Network with LSTM gives 84.24 % accuracy**
