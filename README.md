# 🎬 Movie Recommender System

A simple and interactive movie recommendation web app built using **Streamlit**. It suggests similar movies based on a selected title using a precomputed similarity matrix.

---

## 📸 App Preview

### Input Image : 
![Screenshot 2025-06-25 153654](https://github.com/user-attachments/assets/d1c624b2-abac-4810-96ed-330a8c977d1c)

### Output Output : 
![Screenshot 2025-06-25 153610](https://github.com/user-attachments/assets/bf7f8517-e890-4da4-9ff7-127bf001390e)

---

## 🗂️ Project Structure
#### ├── app.py # Streamlit app
#### ├── movie_dict.pkl # Movie data
#### ├── similarity.pkl # Similarity matrix
#### ├── requirements.txt # Dependencies
#### ├── README.md # This file
#### └── movie-recommender-system.ipynb # Jupyter notebook (optional)

---
### App Link: 
https://movie-recommender4-1nqi.onrender.com

## 🧠 How It Works
1. **movie_dict.pkl** holds movie titles and metadata.

2. **similarity.pkl** stores pairwise similarity scores.

3. When a user selects a movie, top 5 similar titles are displayed.

## 🌐 Deploy on Render
### Start Command:
streamlit run app.py --server.port $PORT


