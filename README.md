# 📜 Bi-gram Language Model

This project implements a **simple bi-gram language model** to compute **unigrams, bigrams, and their perplexity**.

## 📌 Problem Statement

This problem is inspired by the **LLM course at IIT Delhi**. The objectives of the project are:

- ✅ Write a program to compute **unsmoothed unigrams and bigrams**.
- ✅ Run the **n-gram model** on two different small corpora (e.g., **email text** or **newsgroups**) and compare their statistics.
- ✅ Analyze differences in **common unigrams and bigrams** between the two corpora.
- ✅ Add an option to generate **random sentences** based on the trained model.
- ✅ Add an option to compute the **perplexity of a test set**.

## 📊 Implementation Details

- **Unigram and Bigram Calculation**:
  - Tokenize the text and count the occurrences of **unigrams** and **bigrams**.
  - Compute **probabilities** of each n-gram.
  
- **Corpus Comparison**:
  - Analyze frequency differences between two different corpora.
  - Identify key differences in unigram and bigram statistics.

- **Sentence Generation**:
  - Implemented a **random sentence generator** based on bigram probabilities.

- **Perplexity Calculation**:
  - Computes **perplexity** of a given test set using the trained model.
  - Evaluates how well the model generalizes to unseen data.
