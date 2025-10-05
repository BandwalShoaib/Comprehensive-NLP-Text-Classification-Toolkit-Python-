# Text Processing and Sentiment Analysis Project

## Overview
This project demonstrates **text processing** and **sentiment analysis** on two datasets:

1. **Trip Advisor Reviews** – A dataset containing hotel or travel reviews in CSV format.
2. **Book Reviews** – A dataset containing book reviews in CSV format.

---

## Datasets
- **Trip Advisor CSV**: Contains reviews related to hotels, trips, and destinations.
- **Book Reviews CSV**: Contains user reviews for different books.

---

## Features / Work Done

### 1. Trip Advisor Reviews
- **Text Preprocessing**:
  - Converted text to lowercase
  - Removed stopwords
  - Applied regular expressions to clean the text
  - Performed **lemmatization** and **stemming**
- **Linguistic Analysis**:
  - **POS (Part-of-Speech) Tagging**: Identifying nouns, verbs, adjectives, etc.
  - **NER (Named Entity Recognition) Tagging**: Extracting entities like locations, organizations, and person names

---

### 2. Book Reviews
- **Text Preprocessing**:
  - Lowercasing, removing stopwords, regex cleaning, lemmatization, and stemming
- **Sentiment Analysis**:
  - **TextBlob**: Performed polarity and subjectivity analysis
  - **VADER**: Generated compound sentiment scores for each review
- Visualizations or analysis (optional) to summarize positive, negative, and neutral sentiments

---
Requirements

The main Python libraries used:

pandas

nltk

spacy

textblob

vaderSentiment

re

matplotlib / seaborn (optional for visualizations)