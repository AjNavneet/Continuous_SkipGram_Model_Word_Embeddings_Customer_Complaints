# Continuous Skip-Gram Model for Word Embeddings on Customer Complaints Data

## Project Overview

### Business Overview

In the world of Natural Language Processing (NLP), machines can understand and generate text by learning from vast amounts of data. Word embeddings, which represent words as numerical vectors, are essential for this purpose. You've probably heard of Word2Vec and Count vectorization - two popular algorithms for creating word embeddings. This project provides a basic introduction to Word2Vec and one-hot encoding.

---

### Aim

The aim of this project is to understand the continuous skip-gram algorithm and build a model for generating word embeddings from a set of documents.

---

### Data Description

The dataset used for this project contains more than two million customer complaints about consumer financial products. It includes various columns, with one containing the actual text of the complaint and another indicating the product for which the customer is raising the complaint.

**Note:** The project uses the first 100 complaints for testing purposes, but you can train the model on the entire dataset.

---

### Tech Stack

- Language: `Python`
- Libraries: `pandas`, `torch`, `collections`, `nltk`, `numpy`, `pickle`, `os`, `re`

---

## Approach

1. Introduction to the continuous skip-gram algorithm
2. Data Description
3. Data Preprocessing
   - Handling missing values
   - Conversion to lowercase
   - Punctuation removal
   - Digits removal
   - Removing extra spaces
   - Tokenization
4. Building a Data Loader
5. Creating the Skip-Gram Model using the PyTorch framework
6. Model training
7. Generating Word Embeddings

---

## Modular Code Overview

1. **Input**: Contains the data for analysis, in this case, `complaints.xlsx`.
2. **Output**: Contains pre-trained models and vectorizers for future use.
3. **Source**: Contains modularized code for various project steps, including:
   - `model.py`
   - `data.py`
   - `utils.py`

   These Python files contain useful functions used in `Engine.py`.
4. **config.py**: Contains project configurations.
5. **Engine.py**: The main file to run the entire project, including model training and saving.
6. **skip_gram.ipynb**: The original Jupyter notebook.
7. **processing.py**: Used for data processing.
8. **README.md**: Contains comprehensive instructions and information on running specific files.
9. **requirements.txt**: Lists required libraries with respective versions. Install them using `pip install -r requirements.txt`.

**Note:** The project uses the first 100 complaints for testing purposes, but you can train the model on the entire dataset.

---

## Key Concepts Explored

1. One-Hot Encoding and Word2Vec
2. Understanding Syntactic and Semantic Similarity
3. Word2Vec
4. Central and Context Words
5. The Continuous Skip-Gram Algorithm
6. Negative Sampling
7. Steps to Create Word Embeddings using the Skip-Gram Algorithm
8. Data Preparation for Skip-Gram Model
9. Tokenization using `word_tokenization` from the NLTK library
10. Removing spaces and digits
11. Removing punctuation
12. Creating a data loader for the Skip-Gram model
13. Building the Skip-Gram model
14. Training the Skip-Gram model using CUDA or CPU
15. Using word embeddings to get word vectors


---

