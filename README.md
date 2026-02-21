# 🎵 Content-Based Music Recommendation System

## 📌 Project Overview

Have you ever noticed that after watching a funny video on **YouTube**, you start seeing similar funny videos in your recommendations? That’s the power of **Machine Learning-based Recommender Systems**.

This project demonstrates how to build a **Content-Based Music Recommendation System** using Machine Learning. The system recommends songs similar to a given input song based on metadata such as:

* 🎼 Genre
* 🎤 Artist Name
* 🎶 Track Name

We use the **TCC CEDs Music Dataset**, which contains song metadata including genre, artist information, lyrics, and various audio features.



## 🚀 Features

* Exploratory Data Analysis (EDA)
* TF-IDF Vectorization of song metadata
* Cosine Similarity for finding similar songs
* Top-N song recommendations
* Data visualizations using Matplotlib and Seaborn



## 🧠 Machine Learning Concepts Used

* Content-Based Filtering
* TF-IDF (Term Frequency–Inverse Document Frequency)
* Cosine Similarity
* Text Feature Engineering



## 📂 Dataset

**Dataset Used:** TCC CEDs Music Dataset

The dataset contains:

* Song metadata (track name, artist, genre)
* Scientific audio features (loudness, acousticness, speechiness, etc.)
* Songs spanning nearly 100 years



## 🛠️ Technologies & Libraries Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – TF-IDF Vectorizer & Cosine Similarity

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```



## 🔮 Future Improvements

* Use lyrics for better recommendations
* Add audio feature-based similarity
* Implement collaborative filtering
* Deploy as a web app using Flask or Streamlit
* Integrate with Spotify API
