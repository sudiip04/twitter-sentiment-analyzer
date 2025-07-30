# 🐦 Twitter Sentiment Analyzer using LSTM & NLP

This project is a **Twitter Sentiment Analyzer** built using Natural Language Processing (NLP) techniques and a deep learning model based on **LSTM (Long Short-Term Memory)** networks. It classifies tweets into **Positive**, **Neutral**, or **Negative** sentiments.

---

## 🚀 Project Highlights

- Cleaned and preprocessed real tweet data
- Tokenization and padding using Keras
- Embedding layer + LSTM architecture for sequence modeling
- Sentiment prediction using deep learning
- Performance visualization using accuracy/loss graphs

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK (for NLP preprocessing)
- Jupyter Notebook

---
## 📊 Dataset

> **Note**: Dataset is not included in the GitHub repo due to size/privacy reasons. Please place your `.csv` file (containing tweets and labels) inside the `data/` directory.

Each row in the dataset includes:

- `tweet`: the original tweet text  
- `label`: sentiment category (0 = Negative, 1 = Neutral, 2 = Positive)

---

## 🧪 Model Architecture

```text
Input (tokenized tweets) ➡ Embedding Layer ➡ LSTM ➡ Dense ➡ Softmax

