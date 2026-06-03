# Text Mining and NLP

This repository contains a set of Natural Language Processing and Text Mining projects completed. The projects focus on analysing, classifying, and extracting information from text using rule-based methods, traditional machine learning approaches, and transformer-based models.

The repository includes work on sentiment analysis, topic modeling, topic classification, and named entity recognition/classification. Together, these notebooks demonstrate how unstructured text can be transformed into structured insights through preprocessing, classification, evaluation, and error analysis.

## Project Overview

The goal of this repository is to demonstrate practical experience with applied NLP workflows. The notebooks cover different stages of text analysis, including sentiment classification, topic discovery, supervised topic classification, and named entity recognition.

These skills are relevant to applied AI systems that process user feedback, operational reports, support messages, internal documents, or other forms of unstructured text.

## Repository Structure

```text
Text-Mining-NLP/
│
├── data/
│   └── my_tweets.json
│
├── notebooks/
│   ├── 01_sentiment_analysis_vader_naive_bayes.ipynb
│   ├── 02_topic_modeling_gensim.ipynb
│   ├── 03_topic_modeling_sklearn.ipynb
│   ├── 04_topic_classification_BERT.ipynb
│   └── 05_final_nlp_pipeline.ipynb
│
├── poster/
│   └── text_mining_final_project_poster.pptx
│
├── requirements.txt
├── .gitattributes
└── README.md
```

## Notebook Descriptions

### 01 — Sentiment Analysis with VADER and Naive Bayes

This notebook focuses on sentiment analysis. It compares a rule-based sentiment analysis method, VADER, with a machine learning approach using Scikit-learn and Naive Bayes.

The project includes quantitative evaluation using precision, recall, F1-score, and accuracy. It also includes error analysis to understand why some tweets were misclassified. Different preprocessing settings are explored, including lemmatization, part-of-speech filtering, TF-IDF, Bag-of-Words, and different frequency thresholds.

### 02 — Topic Modeling with Gensim

This notebook explores topic modeling using Gensim. It applies preprocessing and topic modeling techniques to discover hidden themes in a text collection.

### 03 — Topic Modeling with Scikit-learn

This notebook applies topic modeling using Scikit-learn. It works with vectorized text representations and explores how topic modeling can be used to identify themes in a collection of documents.

### 04 — Topic Classification with BERT

This notebook focuses on supervised topic classification using a BERT-based model. It demonstrates experience with transformer-based NLP models and text classification workflows.

### 05 — Final NLP Pipeline

This notebook combines multiple NLP tasks in one final text mining project. It includes sentiment analysis, topic classification, and named entity recognition/classification.

The final project evaluates different NLP methods on official course test sets. The tasks include sentiment analysis, topic classification, and NERC. The project compares VADER and TF-IDF-based methods for sentiment analysis, uses TF-IDF with Logistic Regression for topic classification, and applies spaCy for named entity recognition.

## Data

The repository includes `my_tweets.json`, a small manually labelled dataset of 50 example tweets used for sentiment analysis. Other datasets used in the coursework are not included when they were provided externally or through course materials.

## Skills Demonstrated

* Natural Language Processing
* Text mining
* Sentiment analysis
* Topic modeling
* Topic classification
* Named entity recognition/classification
* Text preprocessing
* Tokenization
* Lemmatization
* Part-of-speech filtering
* Bag-of-Words
* TF-IDF
* VADER sentiment analysis
* Naive Bayes classification
* Logistic Regression classification
* BERT-based classification
* spaCy named entity recognition
* Model evaluation
* Precision, recall, F1-score, and accuracy
* Error analysis
* Python and Jupyter Notebook

## Tools and Libraries

* Python
* Jupyter Notebook
* pandas
* numpy
* scikit-learn
* NLTK
* spaCy
* Gensim
* Transformers / BERT-related tools
* PyTorch

## Relevance to Applied AI

This project is relevant to applied AI because many real-world systems need to process and interpret unstructured text. Similar techniques can be used to classify operational reports, analyse user feedback, extract named entities from documents, identify recurring topics, and support document-based AI workflows.

