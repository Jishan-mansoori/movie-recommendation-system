# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using **Python, Machine Learning, and Streamlit**.
The application recommends movies similar to the one selected by the user and displays **movie posters using the TMDB API**.

---

# 🚀 Features

* 🎥 Recommend similar movies instantly
* 🧠 Content-based recommendation algorithm
* 🖼 Fetch movie posters using TMDB API
* ⚡ Interactive web interface built with Streamlit
* 📊 Movie dataset preprocessing using Pandas & NumPy

---

# 🛠 Tech Stack

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Pickle
* TMDB API

---

# 📂 Project Structure

```
movie-recommendation-system
│
├── data/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
│
├── notebook/
│   └── movie_recommender.ipynb   # model training notebook
│
├── app.py                        # streamlit web app
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

# 🧠 How the Recommendation System Works

1. Movie and credits datasets are loaded.
2. Features such as **genres, keywords, cast, and overview** are combined.
3. Text data is converted into vectors using **CountVectorizer**.
4. **Cosine Similarity** calculates similarity between movies.
5. The system recommends the **top 5 similar movies**.

---

# ⚙️ Setup & Run

## 1️⃣ Clone the repository

```bash
git clone https://github.com/Jishan-mansoori/movie-recommendation-system.git
cd movie-recommendation-system
```

---

## 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Create environment variable

Create a `.env` file in the root directory.

```
TMDB_API_KEY=your_tmdb_api_key
```

Get API key from
https://www.themoviedb.org/settings/api

---

## 4️⃣ Run the notebook to generate model files

Before running the web app, execute the notebook:

```
notebook/movie_recommender.ipynb
```

Run all cells to generate the **pickle files used by the application**.

---

## 5️⃣ Run the Streamlit app

```
streamlit run app.py
```

---

## 6️⃣ Open in browser

```
http://localhost:8501
```

---

# 📊 Dataset

This project uses the **TMDB 5000 Movie Dataset** containing:

* Movie titles
* Genres
* Cast
* Crew
* Keywords
* Overview

---

# 💡 Future Improvements

* Add collaborative filtering
* Deploy on Streamlit Cloud
* Improve UI
* Add movie search autocomplete

---

# 👨‍💻 Author

**Jishan Mansoori**

GitHub:
https://github.com/Jishan-mansoori
