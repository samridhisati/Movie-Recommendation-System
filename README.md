# Movie-Recommendation-System
This is a content-based movie recommender system built using Python and the TMDB 5000 Movie Dataset. It analyzes movie metadata such as overview, cast, crew, genres, and keywords to recommend similar movies.

How It Works:
Utilizes TF-IDF Vectorization to process textual metadata.
Calculates cosine similarity between movie overviews to find similar titles.
Supports user input, allowing you to type in a movie name and get recommendations.

Features:
Popularity-based filtering using weighted rating.
Content-based filtering using movie metadata.
Visualizes top movies based on popularity.

Dataset:
tmdb_5000_movies.csv
tmdb_5000_credits.csv

Technologies Used:
Python
Pandas, NumPy
Scikit-learn (TF-IDF, cosine similarity)
Matplotlib (for visualizations)
