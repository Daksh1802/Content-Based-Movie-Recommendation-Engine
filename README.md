# 🎬 Movie Recommender System (Content-Based)

This is a simple and effective movie recommendation system that suggests similar movies based on content features like cast, director, genre, and keywords. It uses natural language processing (NLP) and cosine similarity to find related titles from a dataset of 4800+ movies.

---

## 📚 Features

- Content-based recommendation using:
  - Cast
  - Director
  - Genres
  - Keywords
- Vectorization using `CountVectorizer` or `TF-IDF`
- Cosine similarity to find most similar movies
- CLI interface for entering a favorite movie and getting 50 similar ones

---

## 🛠️ How It Works

1. Loads movie metadata from a CSV file.
2. Combines important features into a single string.
3. Converts text data into numerical vectors using NLP techniques.
4. Calculates similarity scores between movies.
5. Recommends top 50 movies most similar to the one you like.

---

## 🧪 Example Usage

```bash
$ python recommender.py
Which is your favourite movie? Interstellar

Recommended Movies:
1. The Martian
2. Gravity
3. Inception
...
📁 Project Structure
bash

movie-recommender/
├── data/
│   └── movie_dataset.csv       # Dataset used for recommendations
├── recommender.py              # Main Python script
├── README.md                   # This file
└── requirements.txt            # Python dependencies
📦 Requirements
Install dependencies with:

bash

pip install -r requirements.txt
Contents of requirements.txt:

pandas
numpy
scikit-learn

🙋‍♂️ Author
Made by Daksh Perswal
