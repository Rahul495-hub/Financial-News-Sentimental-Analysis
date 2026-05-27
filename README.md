# Financial News Sentiment Analysis using NLP & Deep Learning

## Overview
This project focuses on analyzing financial news headlines and predicting sentiment using Natural Language Processing (NLP) and Deep Learning techniques. The model classifies financial news into **Positive, Negative, and Neutral** sentiments to help understand market behavior and investor psychology.
The system combines **Doc2Vec embeddings** with an **LSTM (Long Short-Term Memory)** neural network to capture contextual relationships in financial text and generate accurate sentiment predictions.

---

## Features
- Financial news sentiment classification
- NLP-based text preprocessing pipeline
- Feature extraction using **Doc2Vec**
- Deep Learning model using **LSTM**
- Performance evaluation with accuracy metrics
- Data visualization and sentiment distribution analysis
- Converts unstructured financial news into actionable insights

---

## Tech Stack
- Python
- TensorFlow / Keras
- NLTK
- Gensim
- Scikit-learn
- Pandas & NumPy
- Matplotlib / Seaborn

---

## Project Workflow

1. Data Collection & Cleaning  
2. Text Preprocessing  
   - Tokenization  
   - Stopword Removal  
   - Lemmatization  
3. Feature Extraction using Doc2Vec  
4. Sequence Modeling with LSTM  
5. Model Training & Validation  
6. Sentiment Prediction & Evaluation  

---

## Model Architecture

- Input Layer
- Embedding Representation (Doc2Vec)
- LSTM Layers
- Dense Output Layer
- Softmax Activation for Multi-Class Classification

---

## Results

- Achieved effective sentiment classification performance on financial news datasets.
- Successfully identified market sentiment trends from textual financial information.
- Improved contextual understanding of financial language using sequential deep learning models.

---

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/financial-news-sentiment-analysis.git

# Navigate to project directory
cd financial-news-sentiment-analysis

# Install dependencies
pip install -r requirements.txt
