# 🎬 Movie Recommender System

A Content-Based Movie Recommendation System web application built with **Python**, **Pandas**, **Scikit-Learn**, and **Streamlit**. It recommends similar movies based on metadata (genres, keywords, cast, and crew) from the TMDB 5000 Movie Dataset and displays movie posters using The Movie Database (TMDB) API.

---

## 🚀 Features

- 🔍 **Interactive Selection**: Select or search any movie from a dropdown menu.
- 🎯 **Content-Based Filtering**: Calculates similarity scores between movies using vectorization and Cosine Similarity.
- 🖼️ **Poster Fetching**: Dynamically retrieves high-resolution poster images via TMDB API.
- ⚡ **Optimized Deployment**: Compressed model artifacts for fast loading on cloud platforms.

---

## 📁 Project Structure

```text
movie-recommender-system/
├── app.py                 # Streamlit web application interface
├── movie_dict.pkl         # Pickled dictionary containing movie metadata
├── similarity.pkl.gz      # Compressed Cosine Similarity matrix (~49 MB)
├── requirements.txt       # Project dependencies for deployment
└── README.md              # Documentation
```

---

## 🛠️ Local Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Coder200524/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

---

## 🌐 Live Demo

You can deploy and run this app live on [Streamlit Community Cloud](https://share.streamlit.io/).

---

## 📜 License
This project is open source and available under the [MIT License](LICENSE).
