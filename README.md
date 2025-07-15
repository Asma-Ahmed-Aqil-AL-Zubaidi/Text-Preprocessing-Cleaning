#  Text Cleaning and Preprocessing Pipeline

This project demonstrates a complete pipeline for **cleaning and preprocessing raw text data**, useful for Natural Language Processing (NLP) tasks such as sentiment analysis, topic modeling, or text classification.

##  Key Features

- Removal of:
  - HTML tags
  - URLs
  - Emojis
  - Punctuation
  - Numbers
  - Extra whitespace
  - Repeated characters (e.g., "soooo" → "soo")

- Text normalization:
  - Lowercasing
  - Lemmatization (with `nltk`)
  - Stopword removal
  - Handling contractions and negations

##  Technologies Used

- Python
- NLTK
- Regular Expressions (`re`)
- Emoji package
- Pandas

