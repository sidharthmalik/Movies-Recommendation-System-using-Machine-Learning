📌 Project Overview
This project implements a Movie Recommendation System that suggests movies to users based on similarity between movies using machine learning techniques.
The system analyzes movie metadata such as genres, keywords, cast, and overview to recommend similar movies. It follows a content-based filtering approach, making recommendations without requiring user ratings.
🎯 Objective
To build a recommendation engine that:
Takes a movie as input
Finds similar movies using feature similarity
Returns top recommended movies
This project demonstrates practical applications of:
Data preprocessing
Feature engineering
Natural Language Processing (NLP)
Cosine similarity
Machine learning pipelines
📊 Dataset
Dataset used: TMDB Movie Dataset (from Kaggle)
Contains information such as:
Movie title
Genres
Overview
Keywords
Cast & crew
🛠 Technologies Used
Python
Pandas
NumPy
Scikit-learn
NLTK
Jupyter Notebook
⚙️ Methodology
1. Data Cleaning
Removed null values
Selected relevant columns
Converted text fields into usable format
2. Feature Engineering
Combined important features into a single column:
Genres
Keywords
Overview
Cast
Director
Text was cleaned and stemmed for better similarity results.
3. Vectorization
Used CountVectorizer / TF-IDF to convert text into numerical vectors.
4. Similarity Calculation
Applied Cosine Similarity to measure closeness between movies.
5. Recommendation Function
Created a function that:
Accepts movie title
Finds closest matches
Returns top 5 recommended movies
✅ Results
The model successfully recommends movies with similar themes, genres, and content.
