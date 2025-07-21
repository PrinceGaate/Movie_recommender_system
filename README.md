# 🎬 Movie Recommender System (TMDB Dataset)

A fully functional **Content-Based Movie Recommendation Engine** built from scratch using the TMDB 5000 Movie Dataset. This project analyzes movie metadata like genres, cast, crew, keywords, and overviews to recommend movies similar to a selected title.

---

## 📌 Project Overview

This project demonstrates the creation of a content-based recommender system using metadata and NLP techniques. By combining multiple textual features, the system identifies similar movies based on their content and suggests top recommendations.

### 🎯 Objectives:
- Build a **recommender engine** that suggests similar movies based on content
- Use **NLP and vectorization techniques** for text-based analysis
- Implement **cosine similarity** to compare movie features
- Enable users to input a movie name and receive suggestions instantly

---

## 🧠 Concepts Used

- Natural Language Processing (NLP)
- Feature Engineering (combining genres, cast, crew, etc.)
- CountVectorizer / TF-IDF Vectorization
- Cosine Similarity
- Exploratory Data Analysis (EDA)
- Building Scalable Functions

---

## 🗂 Files in This Repository

| File / Folder               | Description                                    |
|----------------------------|------------------------------------------------|
| `notebook/movie_recommender.ipynb` | Jupyter Notebook containing full implementation |
| `data/tmdb_5000_movies.csv`        | Dataset of 5000 movies from TMDB              |
| `data/tmdb_5000_credits.csv`       | Cast and crew information                     |
| `README.md`                        | Project documentation                         |
| `requirements.txt` (optional)      | Python dependencies (coming soon)             |

---

## 📊 Dataset

- **Source**: TMDB (via Kaggle)
- **Files used**:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

These datasets contain details like movie overviews, genres, keywords, cast, crew, and more.

---

## 💻 Tech Stack

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- NLTK or SpaCy (optional)
- Jupyter Notebook

---

## 🔍 How It Works

1. Load and merge movie and credits datasets
2. Extract and combine important features (e.g., overview, cast, crew)
3. Clean and preprocess the text data
4. Vectorize the combined text using `CountVectorizer`
5. Compute **cosine similarity matrix**
6. Build a function to recommend top 5 similar movies

---

## 🎥 Sample Output

