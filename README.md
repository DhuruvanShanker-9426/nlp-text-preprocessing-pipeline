# 🧠 NLP Text Preprocessing Pipeline using NLTK

## 📌 Project Overview

This project demonstrates the fundamental steps involved in Natural Language Processing (NLP) using Python and NLTK. It focuses on transforming raw text data into a clean and structured format suitable for machine learning models.

---

## 🎯 Objectives

* Understand NLP preprocessing pipeline
* Perform sentence and word tokenization
* Remove stopwords and punctuation
* Apply stemming and lemmatization
* Perform Part-of-Speech (POS) tagging
* Analyze vocabulary and word distribution

---

## 📝 Input Text

A sample paragraph is used as a corpus to perform all NLP operations step-by-step.

---

## ⚙️ Steps Performed

### 1️⃣ Sentence Tokenization

* Split the paragraph into individual sentences

### 2️⃣ Word Tokenization

* Split sentences into words (tokens)

### 3️⃣ Stopword Removal

* Removed common words like *is, the, and*

### 4️⃣ Text Cleaning

* Converted text to lowercase
* Removed punctuation and non-alphabetic words

### 5️⃣ POS Tagging

* Identified grammatical roles (noun, verb, etc.)

### 6️⃣ Stemming

* Reduced words to root form using Snowball Stemmer

### 7️⃣ Lemmatization

* Converted words into meaningful base forms using WordNet

### 8️⃣ Vocabulary Analysis

* Calculated unique words in each sentence
* Computed overall vocabulary size

---

## 🧰 Technologies Used

* Python 🐍
* NLTK (Natural Language Toolkit)

---

## 📦 Installation

```bash
pip install nltk
```

```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
```

---

## 📊 Key Learnings

* Importance of text preprocessing in NLP
* Difference between stemming and lemmatization
* Role of POS tagging in understanding text
* How raw text is converted into structured data

---

## 🚀 Future Improvements

* Add TF-IDF / Bag of Words
* Build a simple sentiment analysis model
* Use spaCy for comparison
* Apply on real-world datasets

---

## 🙌 Conclusion

This project provides a strong foundation in NLP preprocessing and prepares the data for further machine learning tasks.