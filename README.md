# Indian Recipe Word Embeddings & News Category Classification Using FastText

## Project Overview

This project explores two Natural Language Processing (NLP) tasks using **FastText**:

1. **Indian Recipe Word Embeddings**: 
   We use an **unsupervised FastText model** to generate word embeddings for Indian recipes. The embeddings capture semantic relationships between different ingredients and cooking methods, making it easier to analyze and group similar recipes based on their content.

2. **News Category Classification**: 
   We employ a **supervised FastText model** to classify news articles into predefined categories. The model is trained on a labeled dataset of news articles, where each article belongs to a specific category such as politics, sports, entertainment, etc.

## Why FastText?

FastText is a powerful library developed by Facebook AI Research (FAIR). It's an extension of Word2Vec that improves upon traditional word embedding techniques by considering subword information (character n-grams). This makes FastText particularly useful for:

- **Handling out-of-vocabulary (OOV) words**: FastText can generate embeddings even for rare or unseen words by breaking them into smaller subword units.
- **Dealing with morphologically rich languages**: In languages like Indian languages with a lot of inflections, FastText performs better than traditional word embedding models.
- **Efficient training**: FastText offers fast training time compared to other embedding methods, and its supervised mode is well-suited for text classification tasks.

## Installation

To install FastText, you can use the following command:

```bash
pip install fasttext
