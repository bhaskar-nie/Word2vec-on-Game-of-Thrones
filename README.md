# Game of Thrones Word2Vec

Apply Word2Vec to explore semantic relationships between characters, locations, and themes in the **Game of Thrones** book series (A Song of Ice and Fire) by George R. R. Martin.

## 📘 Project Overview

This project uses a cleaned and segmented version of the *Game of Thrones* books to train a Word2Vec model. The objective is to gain insights into character relationships, narrative structures, and world-building by analyzing contextual similarities in the text.

## 📁 Dataset

**Source**: [Kaggle – Game of Thrones Books Dataset](https://www.kaggle.com/khulasasndh/game-of-thrones-books)

**Files Included**:

* `book_1.csv`
* `book_2.csv`
* `book_3.csv`
* `book_4.csv`
* `book_5.csv`

Each file contains text from one of the first five books in the series, split by chapters and cleaned for analysis.

## 🧠 NLP Approach

The Word2Vec model is trained using the `gensim` library. The workflow includes:

* Text cleaning and tokenization
* Stopword removal
* Word2Vec training using Skip-Gram model
* Similarity queries and vector exploration
* Visualization of word embeddings using t-SNE or PCA

## 🔍 Example Analyses

* Find the most contextually similar characters to "Jon", "Arya", or "Daenerys"
* Explore analogies like: "King" is to "Throne" as "Winterfell" is to what?
* Visualize clusters of character names and key nouns

## ⚙️ Requirements

* Python 3.x
* Gensim
* NLTK
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## 📌 Future Ideas

* Compare embeddings from different books or POV characters
* Integrate named entity recognition (NER) for more accurate character tracking
* Build an interactive web app for exploring vector space relationships

## 📚 References

* Gensim Documentation: [https://radimrehurek.com/gensim/](https://radimrehurek.com/gensim/)
* Kaggle Dataset: [https://www.kaggle.com/khulasasndh/game-of-thrones-books](https://www.kaggle.com/khulasasndh/game-of-thrones-books)
* A Wiki of Ice and Fire: [https://awoiaf.westeros.org/](https://awoiaf.westeros.org/)

---

*This project is for educational purposes. All book content remains the intellectual property of the author and publisher.*

---
