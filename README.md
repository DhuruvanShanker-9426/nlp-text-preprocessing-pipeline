# 🧠 NLP Practice using Python, NLTK, Regex, and spaCy

## 📘 Project Overview

This repository contains my practice work on **Natural Language Processing (NLP)** using Python.

It includes beginner-friendly hands-on notebooks covering **NLTK**, **Regular Expressions**, and **spaCy**.  
The main goal of this repository is to understand how raw text is processed, cleaned, analyzed, and converted into a useful format for NLP and Machine Learning tasks.

---

## 🎯 Objectives

### 🧠 NLP Objectives

- Understand the basic NLP preprocessing pipeline
- Perform sentence tokenization and word tokenization
- Remove stopwords and punctuation
- Convert text into lowercase
- Apply stemming and lemmatization
- Perform Part-of-Speech tagging
- Understand vocabulary and word distribution
- Analyze token-level information using spaCy
- Perform dependency parsing
- Identify named entities from text
- Check similarity between texts

### 🔍 Regex Objectives

- Understand pattern matching in text
- Extract numbers, words, vowels, hashtags, and emails
- Remove special characters from text
- Search for specific patterns inside strings
- Split text using multiple separators
- Validate whether certain patterns exist in text
- Practice different regex functions using Python’s `re` module

---

## 📂 Folder Structure

    NLP_Practice/
    │
    ├── NLTK/
    │   ├── nlp-practice.ipynb
    │   └── regex_practice.ipynb
    │
    └── Spacy/
        └── spacy_practice.ipynb

---

## 📒 Notebooks Included

| Notebook | Description |
|---|---|
| `nlp-practice.ipynb` | Basic NLP preprocessing using NLTK |
| `regex_practice.ipynb` | Regex practice for text extraction and pattern matching |
| `spacy_practice.ipynb` | NLP practice using spaCy tokenization, POS, NER, dependency parsing, and similarity |

---

## ⚙️ NLP Steps Practiced using NLTK

### 1️⃣ Sentence Tokenization

Split a paragraph into individual sentences.

### 2️⃣ Word Tokenization

Split sentences into individual words or tokens.

### 3️⃣ Stopword Removal

Removed common words such as `is`, `the`, and `and`, which may not add much meaning in some NLP tasks.

### 4️⃣ Text Cleaning

Performed basic text cleaning such as:

- Converting text to lowercase
- Removing punctuation
- Removing non-alphabetic words

### 5️⃣ POS Tagging

Identified the grammatical role of each word, such as noun, verb, adjective, etc.

### 6️⃣ Stemming

Reduced words to their root form using **Snowball Stemmer**.

Example:

    running → run
    studies → studi

### 7️⃣ Lemmatization

Converted words into meaningful base forms using **WordNet Lemmatizer**.

Example:

    running → run
    better → good

### 8️⃣ Vocabulary Analysis

Practiced finding:

- Unique words in text
- Vocabulary size
- Word distribution

---

## 🔍 Regex Tasks Practiced

The regex notebook includes practice on:

- Extracting numbers from text
- Checking whether a string starts with a specific word
- Finding the first number from a string
- Finding vowels from text
- Extracting only words
- Removing special characters
- Extracting fixed-length numbers
- Matching different word spellings
- Replacing multiple spaces with a single space
- Splitting text using multiple separators
- Extracting email addresses
- Checking whether digits exist in text
- Extracting hashtags
- Extracting capitalized words

---

## ⚡ spaCy Concepts Practiced

The spaCy notebook includes practice on:

### 1️⃣ Loading spaCy Models

Practiced loading English language models.

Example:

    import spacy

    nlp = spacy.load("en_core_web_sm")

### 2️⃣ Custom Tokenizer

Practiced adding custom tokenizer rules using `ORTH`.

### 3️⃣ Sentencizer

Used spaCy sentencizer to split text into sentences.

### 4️⃣ Token Attributes

Practiced different token attributes such as:

- `like_email`
- `like_url`
- `is_currency`
- `shape_`
- `is_alpha`
- `is_stop`
- `is_punct`

### 5️⃣ Dependency Parsing

Analyzed the relationship between words in a sentence using:

- `token.head`
- `token.children`
- `token.dep_`

### 6️⃣ Named Entity Recognition

Identified entities such as:

- Person names
- Locations
- Organizations
- Dates
- Money
- Countries

### 7️⃣ Lemmatization

Practiced finding the base form of words using spaCy.

### 8️⃣ Part-of-Speech Tagging

Identified grammatical categories of words using:

    token.pos_

### 9️⃣ Similarity Checking

Practiced checking similarity between texts using spaCy word vectors.

### 🔟 Visualization using displaCy

Practiced visualizing:

- Dependency parsing
- Named entities

---

## 🧰 Technologies Used

- Python
- NLTK
- spaCy
- Regular Expressions `re`
- Jupyter Notebook

---

## 🚀 How to Run This Project

1. Clone the repository:

       git clone https://github.com/your-username/nlp-python-practice.git

2. Move into the project folder:

       cd nlp-python-practice

3. Open Jupyter Notebook.

4. Run the notebooks inside the `NLTK` and `Spacy` folders.

---

## 📊 Key Learnings

Through this practice, I learned:

- How raw text is processed in NLP
- How sentence tokenization and word tokenization work
- Why stopword removal is used
- Difference between stemming and lemmatization
- How POS tagging helps understand word roles
- How regex is useful for text extraction and cleaning
- How spaCy processes text using tokens, entities, and dependencies
- How dependency parsing shows relationships between words
- How Named Entity Recognition extracts important information from text
- How text similarity can be checked using spaCy

---

## 🔮 Future Improvements

- Add Bag of Words implementation
- Add TF-IDF vectorization
- Practice text classification
- Build a sentiment analysis model
- Apply NLP techniques on real-world datasets
- Add more advanced regex examples
- Compare NLTK and spaCy preprocessing methods
- Create an end-to-end NLP mini project

---

## 🙌 Conclusion

This repository helped me build a strong foundation in **NLP preprocessing**, **Regex-based text processing**, and **spaCy-based text analysis**.

These concepts are important for working on real-world NLP, Data Analysis, Machine Learning, and AI projects.

---

## 👨‍💻 Author

**Dhuruvan Shanker R**

Aspiring Data Analyst / Data Scientist interested in Python, NLP, Machine Learning, and AI.