# 🎬 Movie Recommendation System

An interactive recommendation engine that suggests movies based on user input. Built with Python, content-based and/or collaborative filtering techniques, and presented via a sleek Streamlit interface.

## 🚀 Live Demo

[Try it here](https://uw7rpx7nwmnf6wqy89bbhm.streamlit.app/)

## 📖 Project Overview

Objective: Recommend movies to users based on selected titles, genres, or rating patterns.

Approach:

Content-based filtering — recommends movies similar in genre, overview, or metadata.

Collaborative filtering — suggests movies based on user-rating similarity.

Can be extended to hybrid methods for improved personalization.

Features:

Clean input through a dropdown or search bar.

Personalized & similar movie recommendations.

Real-time interaction via Streamlit dashboard.

Optionally includes poster visuals, fuzzy search, or TMDb integration.

## 📂 Repository Structure

/Movie_Recommendation_System

│── data/                         # Datasets like movies.csv, ratings.csv

│── app.py                        # Streamlit app for recommendations

│── model.py                      # Recommendation logic

│── requirements.txt              # Project dependencies

│── README.md                     # You’re here!


## ⚡ Getting Started

### 1️⃣ Clone the repository

git clone https://github.com/abhinav744/Movie_Recommendation_System.git

cd Movie_Recommendation_System

### 2️⃣ (Optional) Set up a virtual environment

python -m venv venv

source venv/bin/activate  # Windows: venv\Scripts\activate

### 3️⃣ Install dependencies

pip install -r requirements.txt

### 4️⃣ Run the Streamlit app

streamlit run app.py

## 🛠 How It Works

Data Input: Loads movie metadata and ratings.

Preprocessing: Encodes text, computes embeddings or similarity matrices.

Recommendation Engine:

Content-based: Uses cosine similarity on vectors (e.g., TF-IDF of overviews).

Collaborative filtering: Uses user–item rating patterns to find similar users or items.

Output: Displays top recommended movies, optionally with posters or metadata.

## 🚀 Future Enhancements

Add Hybrid recommendations (combining content-based and collaborative filtering).

Include poster visuals via TMDb.

Improve search with fuzzy matching for user-friendly input.
