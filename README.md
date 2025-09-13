# Task 4 — Smart Movie Recommendation System 🎬

## 📌 Overview
This is a **content-based movie recommendation system** built with Python.  
It works with both **Hollywood movies** (from the TMDB dataset) and **Bollywood movies** (added manually).  

Users can search for a movie, and the system suggests 5 similar titles.

---

## 🚀 Features
- Works for Bollywood and Hollywood movies
- Tkinter GUI with modern dark theme and animated text
- Recommends top 5 movies based on cosine similarity
- Uses cast, crew, genres, and plot overview for similarity

---

## 🛠️ Tech Stack
- Python (pandas, sklearn, customtkinter)
- NLP: CountVectorizer
- Similarity: Cosine Similarity
- Dataset: TMDB 5000 Movies + Credits + 20 Bollywood films (manually added)

---

## 🎥 Demo
![Demo Screenshot](demo.png)

---

## 📚 Concepts Learned
- How to build recommendation engines
- Text preprocessing and feature extraction
- Using **CountVectorizer** for NLP
- Applying **cosine similarity** to calculate closeness between items
- GUI design with CustomTkinter

---

## ▶️ How to Run
1. Place `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` in the project folder.
2. Install dependencies:
   pip install pandas scikit-learn customtkinter tkshadowfy
3.Run the recommender:
   Task 4.py
4.Enter a movie title (e.g., 3 Idiots or Avengers) and get recommendations instantly!

