# Mental-Health-Status-with-HuggingFace-Transformers-BERT


This project implements a state-of-the-art Natural Language Processing (NLP) pipeline for detecting human emotions in text. It leverages the **BERT (Bidirectional Encoder Representations from Transformers)** architecture, specifically utilizing the Hugging Face `transformers` library and the **PyTorch** deep learning framework.

## Project Overview
The system is designed to take raw text input, preprocess it, and classify it into specific emotional categories. The implementation is optimized for high-performance inference using **NVIDIA T4 GPU** acceleration (via Google Colab).

### Key Technical Specs:
* **Model Architecture**: BERT-based Sequence Classification (`AutoModelForSequenceClassification`).
* **Tokenizer**: BERT Pre-trained Tokenizer with a `max_length` of 200 tokens.
* **Frameworks**: PyTorch, Hugging Face Transformers.
* **Environment**: Optimized for Python 3 with GPU support.

Here is how the UI looks like <img width="1470" height="956" alt="Screenshot 2026-01-08 at 5 16 14 PM" src="https://github.com/user-attachments/assets/cfe10c14-b3fa-43bb-98ba-2bf646f9ac29" />


The evaluation:

<img width="789" height="686" alt="Screenshot 2026-01-08 at 6 10 53 PM" src="https://github.com/user-attachments/assets/0b2fd117-424c-4952-9bc6-b9cfe11bdf7f" />
<img width="553" height="265" alt="Screenshot 2026-01-08 at 6 10 31 PM" src="https://github.com/user-attachments/assets/75a8bdcb-0c55-4db7-ab77-e5897ec2a298" />
