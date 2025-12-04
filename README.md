<h1 align="center">🎬 Movie Recommender System</h1>

<p align="center">
  <strong>A simple end-to-end movie recommendation system built using Python, Pandas, Scikit-Learn, Cosine Similarity, and Vectorization Techniques, deployed with Streamlit.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-1.30-orange?logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Scikit--Learn-1.2.2-green?logo=scikitlearn&logoColor=white" alt="Scikit-Learn">
</p>

---

## 🔹 Project Overview

This project takes a dataset of movies, processes textual features, converts them into numerical vectors, and recommends the **most similar movies** based on **cosine similarity**.  
A full **Streamlit web app** is included for interactive use.

🎥 **Watch the demo video:**  

[![Watch the demo](https://img.youtube.com/vi/XNjGYLhOfNY/0.jpg)](https://youtu.be/XNjGYLhOfNY)


---

## 🧠 How It Works

1. **Data Preprocessing**  
   - Cleaning and merging relevant features (genres, keywords, cast, crew, etc.)  
   - Converting text into structured formats

2. **Vectorization**  
   - Using **CountVectorizer** or **TF-IDF** to convert text into numeric vectors  

3. **Cosine Similarity**  
   - Measures similarity between movies  
   - Provides top recommendations for a selected movie

---

## 📊 Dataset Used

- `tmdb_5000_movies.csv`  
- `tmdb_5000_credits.csv`  


---

## 🏗️ Project Structure

```text
Movie Recommender System/
├── Demo.ipynb              # Notebook for preprocessing & model building
├── tmdb_5000_movies.csv    # Dataset
├── tmdb_5000_credits.csv   # Dataset
├── app.py                  # Streamlit web app
├── .gitignore              # Ignore large model files
└── README.md               # Project documentation
