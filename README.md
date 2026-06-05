# Multilingual Vaccine Hesitancy Detection

## Overview

This project investigates vaccine hesitancy detection in multilingual social media comments using traditional machine learning, deep learning, and transformer-based approaches.

The dataset consists of English, Hindi, and code-mixed YouTube comments manually annotated into three classes:

* Pro-vaccine
* Anti-vaccine
* Neutral

## Models Implemented

* TF-IDF + LinearSVC
* Convolutional Neural Network (CNN)
* Multilingual BERT (mBERT)

## Dataset

* ~3,500 collected YouTube comments
* 320 manually labelled comments
* English, Hindi, and code-mixed content

## Results

| Model              | Accuracy | Macro F1 |
| ------------------ | -------- | -------- |
| TF-IDF + LinearSVC | 56.25%   | 54.92%   |
| CNN                | 65.62%   | 62.19%   |
| mBERT              | 57.81%   | 57.59%   |

## Key Findings

* CNN achieved the best overall performance.
* Preserving multilingual characters improved classification quality.
* Transformer models did not outperform simpler architectures under limited training data.
* Temporal analysis revealed event-driven vaccine discussions.

## Technologies

Python, Scikit-learn, TensorFlow/Keras, Transformers, Pandas, NumPy, Matplotlib, NLP

## Future Work

* Larger annotated datasets
* XLM-RoBERTa and IndicBERT
* Semi-supervised learning
* Multimodal misinformation detection
