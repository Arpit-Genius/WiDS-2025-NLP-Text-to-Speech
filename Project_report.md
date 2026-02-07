# Week 1 - Foundation of NLP
## Overview
This repository demonstrates the fundamentals of Natural Language Processing (NLP), including text preprocessing, feature extraction, and basic machine learning for text classification. The project focuses on building practical skills in handling text data, transforming it into machine-readable formats, and evaluating models

## Learning Outcomes

### Introduction to NLP

- Understanding what NLP is and its applications.
- Concepts of tokens, types, and corpora.
- Insights into word embeddings and vector representations of text.

### Text Preprocessing Techniques

- Tokenization: Splitting text into meaningful units.
- Stemming vs Lemmatization: Reducing words to their root forms.
- Stopword Removal: Eliminating common words that don’t add value.
- N-grams: Capturing sequences of words to preserve context.

### Feature Extraction for NLP

- Representing text using Bag-of-Words (BoW).
- Computing TF-IDF for weighted word importance.

### Basic Machine Learning for Text

- Training a classifier on text data (IMDb movie reviews).
- Understanding evaluation metrics: Accuracy, F1-score, BLEU (overview).

### Practical Implementation Skills

- Implementated tokenization and stemming using NLTK.
- Built a TF-IDF based sentiment classifier(IMDb).

# WEEK 2 - Deep Learning for NLP

## Learning Outcomes

### Concepts

- Learned the concept of **word embeddings** and how words are represented as dense vectors.
- Studied popular embedding techniques - **Word2Vec**.
- Understood the role of **neural networks in NLP**.
- Learned the working principles of **Recurrent Neural Networks (RNN)**, **GRU**, and **LSTM**.
- Gained an overview of the **attention mechanism** and its importance in sequence modeling.


### Coding Tasks

- Trained **Word2Vec** on a small text corpus.
- Implemented an **LSTM-based sentiment classification model**.
- Visualized learned word embeddings using **t-SNE** for dimensionality reduction.

### Mini-Project

Compared and analysed the below approaches on a given dataset:
  - **TF-IDF + Logistic Regression**
  - **LSTM-based classifier**

# WEEK 4 - Introduction to Speech Processing
## CONCEPTS
What Is Speech?  

Audio Signal Basics - Sampling rate (Nyquist theorem), Amplitude & dynamic range, Mono vs stereo, Bit depth  

Time–Frequency Representations - Short-Time Fourier Transform (STFT), Spectrograms, Log spectrograms, Why spectrograms?  

Mel Scale & MFCCs - Human auditory perception, Mel frequency scale, Mel spectrograms, MFCC pipeline(STFT, Mel filterbanks, Log compression, DCT)  

Speech Recognition Approaches - Classical STT, Neural STT

## CODING TASKS
AUDIO LOADING and INSPECTION - Loaded .wav files(M1F1-int16-AFsp.wav), Checked duration and sampling rate, Normalized amplitude  

VISUALISATION - Plotted waveform, spectogram, Mel spectrogram, MFCCs  

FEATURE EXTRACTION PIPELINE - Framing and windowing, feature normalization  

Colab Notebook Link - https://colab.research.google.com/drive/13wZpJ91EuW9gjLH2I_oaFxs9PgWpN6Ds?usp=sharing

### KEYWORD SPOTTING MODEL
TASK - Binary classification: “yes” vs “no”  

DATA -  
YES samples  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_jackson_0.wav  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_george_0.wav  
!wget -q -P data/yes https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/0_nicolas_0.wav  

NO samples  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_jackson_0.wav  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_george_0.wav  
!wget -q -P data/no https://github.com/Jakobovski/free-spoken-digit-dataset/raw/master/recordings/1_nicolas_0.wav   
