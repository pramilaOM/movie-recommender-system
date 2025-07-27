# 🎬 Movie Recommender System (Collaborative Filtering)

This project implements a simple **movie recommender system** using **collaborative filtering** in Python. It predicts user preferences based on past behavior and similar users’ ratings. Built entirely in **Google Colab**, this project demonstrates the core concepts of recommendation engines using real-world movie rating data.

---

## 📌 Features

- ✅ Movie recommendation using **user-based collaborative filtering**
- ✅ Correlation-based similarity between movies
- ✅ Visualization of rating distributions
- ✅ Filtering based on number of ratings to improve recommendation quality
- ✅ Interactive data exploration using `pandas`, `matplotlib`, and `seaborn`

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Dataset

- `file.tsv`: User ratings (user_id, item_id, rating, timestamp)
- `Movie_Id_Titles.csv`: Maps movie IDs to movie titles

> Note: Make sure to place both datasets in the same directory as the notebook or update the path accordingly.

---

## 🚀 How It Works

1. **Data Loading**  
   Load user ratings and movie titles using `pandas`.

2. **Data Cleaning & Merging**  
   Merge both datasets on `item_id` to associate ratings with movie titles.

3. **Exploratory Data Analysis**  
   - Average rating per movie
   - Number of ratings per movie
   - Visualizations using histograms

4. **Building the Recommender**  
   - Construct a user-movie matrix
   - Compute correlations between movies
   - Filter based on movies with significant number of ratings (e.g., >100)

5. **Get Recommendations**  
   - Recommend movies similar to “Star Wars (1977)” or “Liar Liar (1997)”

---

## 📊 Sample Output

Top movies similar to **Star Wars (1977)** with >100 ratings:
