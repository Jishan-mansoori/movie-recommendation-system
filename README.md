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
│   └── movie_recommender.ipynb
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

# 🧠 How the Recommendation System Works

1. Movie and credits datasets are loaded.
2. Important features such as **genres, keywords, cast, and overview** are combined.
3. Text data is converted into numerical vectors using **CountVectorizer**.
4. **Cosine Similarity** is used to compute similarity between movies.
5. When a user selects a movie, the system recommends the **top 5 most similar movies**.

---

# 🔑 Environment Variables

This project uses the **TMDB API** to fetch movie posters.

Create a `.env` file in the root directory and add:

```
TMDB_API_KEY=your_tmdb_api_key
```

You can get your API key from:
https://www.themoviedb.org/settings/api

---

# ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/Jishan-mansoori/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2️⃣ Create virtual environment (optional)

```
python -m venv venv
```

Activate environment:

Windows

```
venv\Scripts\activate
```

Mac/Linux

```
source venv/bin/activate
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Run the application

```
streamlit run app.py
```

---

### 5️⃣ Open in browser

```
http://localhost:8501
```

---

# 📊 Dataset

The project uses the **TMDB 5000 Movie Dataset**, which includes:

* Movie titles
* Genres
* Cast
* Crew
* Keywords
* Movie overview

These features are used to calculate similarity between movies.

---

# 💡 Future Improvements

* Add user authentication
* Deploy on Streamlit Cloud
* Add collaborative filtering
* Improve UI/UX design
* Add search autocomplete

---

# 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

# 👨‍💻 Author

**Jishan Mansoori**

GitHub:
https://github.com/Jishan-mansoori
