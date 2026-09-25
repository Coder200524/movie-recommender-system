# Movie Recommender System

A content-based movie recommendation web application built using Python, Pandas, Scikit-Learn, and Streamlit.

Given a movie selected by the user, the app recommends 5 similar movies based on metadata (genres, keywords, cast, and crew) from the TMDB 5000 dataset, along with movie poster previews fetched via the TMDB API.

---

## How It Works

1. Preprocessed movie metadata (tags, genres, cast, and crew) in a Jupyter Notebook.
2. Built a Content-Based Filtering model using Cosine Similarity to compute similarity scores between movies.
3. Created an interactive Streamlit UI to select movies and view recommendations with poster images.

---

## Repository Contents

- `app.py`: Main Streamlit application script
- `movie-recommender-checkpoint.ipynb`: Jupyter Notebook containing data preprocessing and model creation
- `movie_dict.pkl`: Processed DataFrame dictionary
- `similarity.pkl.gz`: Compressed similarity matrix
- `requirements.txt`: Required Python dependencies

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Coder200524/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Streamlit app:
   ```bash
   streamlit run app.py
   ```
