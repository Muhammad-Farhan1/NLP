# 🧠 Natural Language Processing (NLP) — From Scratch to Sequence Models

A structured, hands-on collection of Jupyter notebooks covering the core concepts of Natural Language Processing — from raw text cleaning all the way to RNN-based sequence models. Each notebook builds on the previous, making this repository ideal for beginners and intermediate practitioners looking to master NLP fundamentals.

---

## 📁 Repository Structure

```
NLP/
├── Datasets/                        # Raw and processed datasets used across notebooks
├── 01_Text_Cleaning_NLP.ipynb       # Removing noise from raw text
├── 02_Text_Preprocessing_NLP.ipynb  # Tokenization, stopwords, stemming & lemmatization
├── 03_Text_Representation_NLP.ipynb # Bag of Words, TF-IDF
├── 04_Word2Vec.ipynb                # Word2Vec theory & training
├── 05_Text_Preprocessing_IMBD.ipynb # Preprocessing applied to the IMDB dataset
├── 06_GloVe.ipynb                   # GloVe embeddings — theory & usage
├── 07_IMDB_Practice.ipynb           # End-to-end practice on IMDB reviews
├── 08_IMDB_Word2Vec.ipynb           # Sentiment classification with Word2Vec
├── 09_GloVe_IMDB.ipynb              # Sentiment classification with GloVe
├── 10_FastText_IMDB.ipynb           # Sentiment classification with FastText
├── 11_RNN_Pytorch.ipynb             # RNN sentiment analysis in PyTorch
└── 12_RNN_Fake_data.ipynb           # RNN training & evaluation on synthetic data
```

---

## 📚 Notebooks Overview

### 🔹 Foundations

| # | Notebook | Description |
|---|----------|-------------|
| 01 | `01_Text_Cleaning_NLP.ipynb` | Removing HTML tags, punctuation, special characters, and other noise from raw text |
| 02 | `02_Text_Preprocessing_NLP.ipynb` | Tokenization, lowercasing, stopword removal, stemming, and lemmatization |
| 03 | `03_Text_Representation_NLP.ipynb` | Converting text to numeric form using Bag of Words (BoW) and TF-IDF |

### 🔹 Word Embeddings

| # | Notebook | Description |
|---|----------|-------------|
| 04 | `04_Word2Vec.ipynb` | Introduction to Word2Vec (CBOW & Skip-gram) and training custom embeddings |
| 06 | `06_GloVe.ipynb` | Understanding Global Vectors (GloVe) and loading pre-trained embeddings |

### 🔹 Applied NLP — IMDB Sentiment Analysis

| # | Notebook | Description |
|---|----------|-------------|
| 05 | `05_Text_Preprocessing_IMBD.ipynb` | Preprocessing the IMDB movie review dataset end-to-end |
| 07 | `07_IMDB_Practice.ipynb` | Full pipeline practice — preprocessing → representation → classification |
| 08 | `08_IMDB_Word2Vec.ipynb` | Sentiment classification on IMDB using Word2Vec embeddings |
| 09 | `09_GloVe_IMDB.ipynb` | Sentiment classification on IMDB using GloVe embeddings |
| 10 | `10_FastText_IMDB.ipynb` | Sentiment classification on IMDB using FastText embeddings |

### 🔹 Sequence Models (PyTorch)

| # | Notebook | Description |
|---|----------|-------------|
| 11 | `11_RNN_Pytorch.ipynb` | RNN implementation in PyTorch for sentiment analysis on IMDB |
| 12 | `12_RNN_Fake_data.ipynb` | RNN for sentiment analysis with full training and evaluation loop on synthetic data |

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Notebooks:** Jupyter Notebook
- **Core Libraries:**
  - `NLTK` — tokenization, stopwords, stemming, lemmatization
  - `scikit-learn` — TF-IDF, BoW vectorization, model evaluation
  - `Gensim` — Word2Vec, FastText training and loading
  - `PyTorch` — RNN implementation and deep learning training loops
  - `NumPy` / `Pandas` — data handling
  - `Matplotlib` / `Seaborn` — visualization

---


---

## 🗂️ Datasets

All datasets used in this repository are stored in the `Datasets/` folder. The primary dataset used for applied tasks is the **IMDB Movie Reviews** dataset — a benchmark for binary sentiment classification (positive / negative reviews).

---

## 📈 Learning Path

```
Text Cleaning → Preprocessing → Representation (BoW / TF-IDF)
    → Word2Vec → GloVe → FastText
        → Applied to IMDB Sentiment Analysis
            → Sequence Models (RNN in PyTorch)
```

Each step introduces a new concept while grounding it in practical, real-world text data.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with 💡 by [Muhammad Farhan](https://github.com/Muhammad-Farhan1)
