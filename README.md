# 🎬 Smart Movie Review Analyzer

A machine learning-powered system that analyzes movie reviews from the IMDB dataset. It includes sentiment classification, neural network models (ANN & CNN), word embeddings, and text summarization.

---

## 📁 Project Structure
```
SmartMovieReviewAnalyzer/
├── Smart_Movie_Review_Analyzer.ipynb   # Main Jupyter Notebook
├── README.md                           # Project documentation
├── requirements.txt                    # Python dependencies
├── .gitignore                          # Files to ignore in Git

```

---

## 🧠 Features

### ✅ Text Classification
- TF-IDF + Logistic Regression (Baseline)
- Deep Learning using ANN
- 1D CNN for text classification

### 🔤 Word Embeddings
- Pre-trained Word2Vec (via `gensim`)
- t-SNE visualization of top 100 word vectors
- Similar review/content-based retrieval

### 📝 Text Summarization
- Extractive summarization using **TextRank**
- Converts long reviews (200+ words) into concise summaries

### 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score

---

## 🚀 How to Run (Google Colab Recommended)
1. Upload the notebook to [Google Colab](https://colab.research.google.com/)
2. Make sure to enable GPU (optional but faster)
3. Run cells step-by-step
4. Dataset will be auto-downloaded via:
```python
from tensorflow.keras.datasets import imdb
```

---

## 🧩 Requirements
Install using:
```bash
pip install -r requirements.txt
```

### Key Libraries
- pandas
- numpy
- scikit-learn
- tensorflow
- keras
- nltk
- gensim
- matplotlib
- seaborn

---

## 🔥 Sample Output
(Optional — include screenshots in `sample_outputs/`)
- Model accuracy: ~85%
- Sample positive/negative predictions
- Visual t-SNE plot
- Summarized reviews using TextRank

---

## 🗂 .gitignore Example
```
__pycache__/
.ipynb_checkpoints/
.env
.DS_Store
*.pyc
*.pkl
*.h5
sample_outputs/
```

---

## 📜 License
This project is licensed under the MIT License.

## 🙌 Credits
- IMDB dataset: [Stanford Sentiment Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- Word2Vec: `gensim`
- Preprocessing: `nltk`
- Modeling: TensorFlow/Keras

---

## ✨ Author
Made with 💻 by Syed Wahidul HaqueAque| GenAI + ML Developer 🚀

