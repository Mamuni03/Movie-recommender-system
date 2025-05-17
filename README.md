🎬 Movie Recommender System
This project is a Content-Based Movie Recommender System built using Python. It helps users find movies similar to their favorites by analyzing various attributes like genres, keywords, cast, and more. The dataset is sourced from the TMDB (The Movie Database) via Kaggle.

📂 Dataset
Source: Kaggle - TMDB Movie Dataset

Contains movie metadata such as:

Title

Overview

Genres

Cast & Crew

Keywords

Popularity, Ratings, Vote Count, etc.

🛠 Features
Data Cleaning & Preprocessing

Feature Engineering (e.g., combining multiple columns into tags)

Cosine Similarity to find similar movies

Recommendation System with movie title as input

Web Interface ( using Streamlit)

📌 Technologies Used
Python

Pandas, NumPy

Scikit-learn

NLTK / SpaCy (for NLP)

Jupyter Notebook

 Streamlit for frontend

🧹 Data Preprocessing Steps
Removed duplicates and null entries

Merged features like genres, keywords, cast, and crew

Extracted the director's name

Combined text features into a single column: tags

Performed text preprocessing (lowercasing, stemming, removing punctuation/stopwords)

Converted text into vectors using CountVectorizer / TF-IDF

Calculated similarity using cosine similarity

💡 How It Works
You input a movie title.

The system finds the top 5 most similar movies using cosine similarity on the tags feature.

It returns a list of recommended movies based on content similarity.

