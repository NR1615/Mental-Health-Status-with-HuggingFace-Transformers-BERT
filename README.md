# Mental-Health-Status-with-HuggingFace-Transformers-BERT


This project implements a state-of-the-art Natural Language Processing (NLP) pipeline for detecting human emotions in text. It leverages the **BERT (Bidirectional Encoder Representations from Transformers)** architecture, specifically utilizing the Hugging Face `transformers` library and the **PyTorch** deep learning framework.

## 🚀 Project Overview
The system is designed to take raw text input, preprocess it, and classify it into specific emotional categories. The implementation is optimized for high-performance inference using **NVIDIA T4 GPU** acceleration (via Google Colab).

### Key Technical Specs:
* **Model Architecture**: BERT-based Sequence Classification (`AutoModelForSequenceClassification`).
* **Tokenizer**: BERT Pre-trained Tokenizer with a `max_length` of 200 tokens.
* **Frameworks**: PyTorch, Hugging Face Transformers.
* **Environment**: Optimized for Python 3 with GPU support.

## 🛠️ Pipeline Features

### 1. Data Cleaning
The notebook includes a dedicated `clean_statement()` function to normalize input text before it reaches the model, ensuring higher accuracy by removing noise from raw strings.

### 2. Tokenization
Utilizes automated padding and truncation to convert text into tensors compatible with BERT's input requirements:
```python
inputs = tokenizer(text, padding=True, truncation=True, max_length=200, return_tensors='pt')
