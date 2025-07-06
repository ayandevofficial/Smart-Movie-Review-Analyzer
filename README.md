# 🎬 Smart Movie Review Analyzer

This project is built as part of a Machine Learning & AI Real-World Assignment.  
It performs sentiment classification on IMDB movie reviews, applies neural networks, and summarizes long reviews.

---

## 🔍 Project Breakdown

### 📌 Part A: Text Classification & Word Embeddings
- IMDB dataset used (via `tensorflow.keras.datasets.imdb`)
- Two approaches:
  - TF-IDF + Logistic Regression
  - Word2Vec embeddings + Averaging + ANN
- t-SNE visualization of top 100 words
- Goal: Achieve 80%+ accuracy ✅

### 📌 Part B: Neural Networks
- Implemented:
  - 3-layer ANN with dropout
  - 1D CNN for review classification
- Compared performance of ANN vs CNN

### 📌 Part C: Text Summarization
- Used **TextRank** (via `summa.summarizer`)
- Summarized long reviews (200+ words) into 2-3 sentence summaries

---

## 🚀 How to Run

1. Open `Smart_Movie_Review_Analyzer.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells top-to-bottom
3. Outputs like accuracy, summaries, and plots will be auto-generated

---

## 📦 Dependencies

Install all requirements with:

```bash
pip install -r requirements.txt
