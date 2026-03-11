# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** that suggests movies similar to a selected movie using **Natural Language Processing (NLP)** techniques.
The model analyzes movie metadata and calculates similarity using **TF-IDF vectorization** and **cosine similarity**.

---

## 🚀 Features

* Content-based movie recommendation
* NLP-based text processing
* Similarity calculation using cosine similarity
* Interactive web interface
* Movie poster integration using TMDB API

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit

---

## 📂 Project Structure

```
movie-recommendation-system
│
├── model.pkl
├── movies.pkl
├── tfidf_matrix.pkl
├── indices.pkl
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd ML-Movie-Recomendation-System
```

---


## 📊 How It Works

1. Movie metadata is cleaned and processed.
2. Text features are converted into numerical vectors using **TF-IDF**.
3. **Cosine similarity** is used to measure similarity between movies.
4. The system returns the **top recommended movies** similar to the selected movie.

---

## 🎥 Example

Input Movie:

```
Godzilla
```

Recommended Movies:

```
Godzilla vs Kong
Pacific Rim
Kong: Skull Island
Jurassic World
Rampage
```

---

## 📸 Future Improvements

* Add movie posters
* Add ratings and overview
* Deploy using cloud platforms
* Improve recommendation algorithm

---

## 👨‍💻 Author

Akash Pandey

---

⭐ If you like this project, please give it a **star** on GitHub!
