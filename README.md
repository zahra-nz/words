# words
# NLP PDF Analysis Project – Analyse de PDF en NLP

## English Version

### Project Summary
This project extracts text from PDF files in French, analyzes keyword contexts, filters stopwords, and calculates semantic similarity using CamemBERT embeddings. It is useful for text analysis, information extraction, and understanding word relationships in French documents.

### Features
- PDF text extraction (`pdfplumber`)
- French text preprocessing (tokenization, stopwords removal)
- Context extraction around a user-specified keyword
- Frequent word analysis
- Semantic similarity analysis using CamemBERT embeddings
- Works entirely in Google Colab

### Installation
Install required Python packages:
```bash
!pip install -U spacy
!python -m spacy download fr_core_news_md
!pip install pdfplumber
!pip install transformers torch nltk scikit-learn

