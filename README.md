# 📚 Book Recommendation System

A **Machine Learning–based Book Recommendation System** built using **Python and Flask**.  
The application recommends books using **popularity-based filtering** and **collaborative filtering** techniques, and provides an interactive web interface for users.

---

## 🚀 Key Features

- ⭐ Popularity-based book recommendations (top-rated books)
- 🤝 Collaborative filtering using **Cosine Similarity**
- 📖 Displays book title, author, and cover image
- 🌐 Flask-based web application
- ⚠️ Error handling for unavailable or invalid book inputs

---

## 🧠 Recommendation Techniques Used

### 1. Popularity-Based Filtering
- Recommends books based on overall ratings and number of reviews
- Ideal for new users (no prior interaction required)

### 2. Collaborative Filtering
- Uses user–item interaction data
- Applies **Cosine Similarity** to find similar books
- Generates personalized recommendations based on user preferences

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Web Framework:** Flask  
- **Development & Analysis:** Jupyter Notebook  
- **Frontend:** HTML, CSS  

---

## 📂 Project Structure

├── app.py
├── model/
│ └── recommender.pkl
├── templates/
│ └── index.html
├── static/
│ └── styles.css
├── notebooks/
│ └── data_analysis.ipynb
├── requirements.txt
└── README.md
