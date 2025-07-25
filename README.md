

# NLP Workshop – Probabilistic and Vector Space Models

## Overview

This repository contains two workshop notebooks designed to guide you through building a complete NLP pipeline and implementing foundational probabilistic language models. The focus is on **n-gram language modeling** (unigram and bigram models) and **text generation using probability distributions**. The primary dataset consists of simulated FAQs generated with ChatGPT, covering a variety of topics.


Each notebook features:
- Step-by-step code for document collection, tokenization, normalization, and vectorization
- Implementation of n-gram models and text generation
- Clear markdown explanations and hands-on exercises
- Collaborative coding and peer feedback best practices

---

## 👥 Team Members

- Babandeep – ID: 9001552  
- Hasyashri Bhatt – ID: 9028501  
- Paula Ramirez – ID: 8963215  

---

## Project Structure
 
- `ProbabilisticLanguageModels.ipynb`  
  - N-gram modeling, text generation, and probabilistic analysis

- `data`  
  - Contains the dataset: a collection of FAQs generated using ChatGPT, with questions and answers on various topics

 
---

### Features:

- Build a complete NLP pipeline: document collection, tokenization, normalization, and vectorization
- Implement and analyze unigram and bigram models
- Explore additive smoothing, conditional probabilities, and random sentence generation
- Practice collaborative coding, debugging, and peer feedback using Git and GitHub

---
 

##  Sample Queries Tested

- Unigram probability calculation for specific words
- Bigram probability calculation for word pairs (e.g., `"financial"`, `"support"`)
- Bigram-based text generation starting with a given seed (e.g., `"he"`)
- Random sentence generation using unigram and bigram models
- Testing additive smoothing on unseen word

## 🚀 Quick Start

```bash
python -m venv venv
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv\Scripts\activate
pip install -r requirements.txt
```

