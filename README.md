# Introductory NLP Class in Glints
---

## Objective
In this notebook, we will learn 2 things
1. Basic preprocessing in NLP
2. Build Text Classification using Bag-of-Words

In the first section, we will experiment with Tokenization, Stopwords, Stemming & Lemmatization.

In the second section, we will experiment build text feature representation using CountVectorier and TfidfVectorizer. We will also learn how to perform Error Analysis and improve the model performance.

## Machine Learning Problem

**Problem Statement**

Given text, predict 20 newsgroups, hence this is a multi-class classification problem. The class distribution is imbalanced.

**Evaluation Metrics**

Macro F1 score. Why? Because we want to measure F1 score for each class and see the overall.

---

## Environment
This notebook run using python 3.7. I use [Anaconda](https://docs.anaconda.com/anaconda/install/) to set the environment.

Install the Anaconda first and then open terminal
```bash
conda create --name new_environment python=3.7 # create new environment
conda activate new_environment # activate the env
pip install -r requirements.txt # install packages in requirements.txt
```
## 
