# NLP — (Natural Language Processing) Notebooks

A hands-on collection of Jupyter notebooks walking through core Natural Language Processing concepts — from raw text cleaning all the way to modern word embeddings — applied to real datasets like IMDB movie reviews.

## 📚 What's inside

The notebooks are numbered to follow a logical learning path: each one builds on the previous, starting with foundational text processing and moving toward sentiment classification with embeddings.

### Foundations

| # | Notebook | Topic |
|---|----------|-------|
| 01 | `01_Text_Cleaning_NLP.ipynb` | Lowercasing, punctuation removal, handling URLs/HTML, special characters, emojis |
| 02 | `02_Text_Preprocessing_NLP.ipynb` | Tokenization, stopword removal, stemming, lemmatization |
| 03 | `03_Text_Representation_NLP.ipynb` | Bag of Words, TF-IDF, n-grams — converting text to numerical features |

### Word Embeddings

| # | Notebook | Topic |
|---|----------|-------|
| 04 | `04_Word2Vec.ipynb` | Word2Vec embeddings (CBOW & Skip-gram) using Gensim |
| 06 | `06_GloVe.ipynb` | GloVe (Global Vectors) pre-trained word embeddings |

### Applied Project — IMDB Sentiment Analysis

| # | Notebook | Topic |
|---|----------|-------|
| 05 | `05_Text_Preprocessing_IMBD.ipynb` | Cleaning & preprocessing the IMDB reviews dataset |
| 07 | `07_IMDB_Practice.ipynb` | Building a baseline sentiment classifier |
| 08 | `08_IMDB_Word2Vec.ipynb` | IMDB sentiment classification using Word2Vec embeddings |
| 09 | `09_GloVe_IMDB.ipynb` | IMDB sentiment classification using GloVe embeddings |
| 10 | `10_FastText_IMDB.ipynb` | IMDB sentiment classification using FastText embeddings |

## 🗂️ Repository structure

```
NLP/
├── Datasets/                          # Raw data used across notebooks
├── 01_Text_Cleaning_NLP.ipynb
├── 02_Text_Preprocessing_NLP.ipynb
├── 03_Text_Representation_NLP.ipynb
├── 04_Word2Vec.ipynb
├── 05_Text_Preprocessing_IMBD.ipynb
├── 06_GloVe.ipynb
├── 07_IMDB_Practice.ipynb
├── 08_IMDB_Word2Vec.ipynb
├── 09_GloVe_IMDB.ipynb
└── 10_FastText_IMDB.ipynb
```

## 🛠️ Tech stack

- **Python 3.8+**
- **Jupyter Notebook**
- **NLTK** — tokenization, stopwords, stemming, lemmatization
- **scikit-learn** — BoW, TF-IDF, classifiers, evaluation metrics
- **Gensim** — Word2Vec, FastText
- **GloVe** — pre-trained embeddings
- **NumPy / Pandas** — data manipulation
- **Matplotlib / Seaborn** — visualization

## 🚀 Getting started

### 1. Clone the repository

```bash
git clone https://github.com/Muhammad-Farhan1/NLP.git
cd NLP
```

### 2. (Recommended) Create a virtual environment

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install numpy pandas scikit-learn nltk gensim matplotlib seaborn jupyter
```

Download the required NLTK resources inside Python:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

Open any notebook from `01_…` onward and run the cells.

## 📊 Dataset

The `Datasets/` folder contains the data used across the notebooks. The **IMDB movie reviews** dataset is the primary dataset used for sentiment classification experiments (notebooks 05–10).

> 💡 If a notebook references a dataset that isn't included due to file size, the original source is referenced inside the notebook itself.

## 🎯 Learning outcomes

By working through these notebooks you'll get hands-on with:

- Cleaning and normalizing messy real-world text
- Classical text representations (BoW, TF-IDF)
- Training your own word embeddings with Word2Vec
- Using pre-trained embeddings (GloVe, FastText)
- Applying embeddings to a real classification task (sentiment analysis)
- Comparing how different embedding strategies affect model performance

## 🤝 Contributing

This is a personal learning repository, but suggestions, corrections, and improvements are welcome. Feel free to open an issue or submit a pull request.

## 📝 License

This project is released for educational purposes. Feel free to use it as a reference for your own NLP learning journey.

## 👤 Author

**Muhammad Farhan**
GitHub: [@Muhammad-Farhan1](https://github.com/Muhammad-Farhan1)

---

⭐ If you found this helpful, consider starring the repo!
