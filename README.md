# Movie Recommendation System

A content-based movie recommendation system built using Python, Machine Learning, and Streamlit.

This application recommends five similar movies based on a selected movie using cosine similarity and displays movie posters using the TMDB API.

---

## Overview

This project uses a content-based filtering approach:

1. Movie metadata (genres, keywords, overview, cast, crew) is combined.
2. Text data is vectorized using NLP techniques.
3. Cosine similarity is computed between movie vectors.
4. The top five most similar movies are recommended.

---

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Streamlit
- TMDB API
- Requests
- Pickle

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
