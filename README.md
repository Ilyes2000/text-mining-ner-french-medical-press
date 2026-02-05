# Text Mining & Named Entity Recognition on French Corpora

This repository contains the complete work for **TP1 and TP2** of the course  
**Text Mining & Chatbots**, taught by **Prof. Sahar Ghannay**.

The project focuses on:
- training and analyzing **word embeddings**,
- applying **deep learning models** for **Named Entity Recognition (NER)**,
- comparing classical neural models with **Transformer-based approaches**,
- evaluating performance on **medical** and **press** French corpora.

---

## Course Information

- **Course**: Text Mining & Chatbots  
- **Instructor**: Sahar Ghannay  
- **Academic level**: Master 2  
- **Institution**: Université Paris-Saclay  

---

##  Authors

- **Ilyes Sais** – ilyes.sais@universite-paris-saclay.fr  
- **Wenchong Pan** – wenchong.pan@universite-paris-saclay.fr  

---

##  Project Overview

The project is divided into **two main practical sessions**:

### TP1 Word Embeddings Training & Analysis
We train and analyze different word embedding models using:
- **Word2Vec (CBOW & Skip-gram)**  
- **FastText (CBOW)**  

These models are trained on two distinct corpora:
- **QUAERO_FrenchMed** (medical domain, small corpus)
- **QUAERO_FrenchPress** (press domain, large corpus)

The embeddings are evaluated qualitatively using **semantic similarity** analysis.

---

### TP2 Named Entity Recognition (NER)

In the second part, the embeddings trained in TP1 are used to perform  
**sentence-level Named Entity Recognition**.

We compare several models:
- **LSTM + Word2Vec embeddings**
- **CNN + FastText embeddings**
- **CamemBERT (Transformer-based model)**

Experiments are conducted on:
- **Medical data**
- **Press data**

All models are evaluated using standard metrics:
**Precision, Recall, F1-score, Accuracy**.

---
# text-mining-ner-french-medical-press
