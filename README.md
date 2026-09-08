# Genomic Mutation Classification using BERT and LSTM

## 📌 Overview

This project presents a hybrid deep learning approach for genomic mutation classification using a BERT-based DNA language model and Long Short-Term Memory (LSTM) network.

DNA sequences are treated as a biological language, where nucleotide patterns are converted into k-mer tokens. A pretrained DNA language model is used to learn contextual representations from the genomic sequences, while an LSTM network captures sequential dependencies in the learned representations.

The system performs binary classification of genomic sequences into:

- Wildtype
- Mutated

The project focuses on genomic/viral sequence classification and demonstrates how transformer-based language models and recurrent neural networks can be combined for biological sequence analysis.

---

## 🎯 Objectives

The main objectives of this project are:

- Convert genomic sequences into meaningful k-mer representations.
- Use a pretrained DNA language model to learn contextual sequence features.
- Use an LSTM network to capture sequential dependencies.
- Build a hybrid BERT + LSTM classification model.
- Handle class imbalance during model training.
- Evaluate the model using Accuracy, F1-Score, and ROC-AUC.
- Develop a deep learning pipeline for genomic mutation classification.

---

## 🧬 Problem Statement

Genomic sequences contain complex patterns that can be difficult to identify using traditional machine learning approaches.

Mutation classification requires understanding both the local patterns and the broader context of nucleotide sequences. Conventional models may have difficulty learning these relationships efficiently.

This project addresses the problem by combining transformer-based contextual feature extraction with LSTM-based sequential learning.

---

## 💡 Proposed Approach

The proposed system follows these major steps:

Raw Genomic Sequence
        ↓
Data Preprocessing
        ↓
6-mer Generation
        ↓
DNA Tokenization
        ↓
Pretrained BERT-based DNA Model
        ↓
Contextual Feature Extraction
        ↓
Bi-directional LSTM
        ↓
Fully Connected Layers
        ↓
Mutation Classification
        ↓
Wildtype / Mutated
