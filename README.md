## Google Colab

(https://colab.research.google.com/drive/1ZXTYjwrtZ9MZanur1xq-Q-IcMu7JcQEQ?usp=sharing)

# ELA-1 — Phishing & Malicious Email Classifier

## Student Details

**Name:** SRINIKETHAN M  (23071A67A2)
**Department:** CSE-CyS, DS and AI&DS  
**Course:** Deep Learning Applications (ELA-1)

---

## Project Title

### Phishing & Malicious Email Classifier using BiLSTM

**Track:** Track 1 — Phishing & Malicious Email Classifier

---

## Project Description

A deep learning-based email classification system that automatically
classifies raw email text into two categories:

- Legitimate
- Phishing/Malicious

The system performs text cleaning, tokenisation, padding and truncation,
followed by a Bidirectional LSTM model for classification.

---

## Dataset

A synthetic dataset containing **2,000 labeled emails** was generated,
which satisfies the requirement of at least 1,500 labeled emails.

The dataset contains:

- 1,000+ legitimate email examples
- 1,000+ phishing/malicious email examples
- Email text
- Class labels

---

## Technologies Used

- Python 3.x
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

---

## Model Architecture

```text
Raw Email
    ↓
Text Cleaning
    ↓
Tokenisation
    ↓
Padding / Truncation
    ↓
Embedding Layer
    ↓
Bidirectional LSTM
    ↓
Dropout
    ↓
Dense Layer
    ↓
Legitimate / Phishing
