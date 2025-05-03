# 🎬 Movie Recommendation System

## 📌 Introduction

In today’s digital world, users are overwhelmed with the abundance of movie choices available across various platforms. As a result, deciding what to watch next has become increasingly difficult. Movie Recommendation Systems offer a practical solution to this issue by helping users discover movies tailored to their preferences, based on data and intelligent algorithms.

This project aims to build a **Content-Based Movie Recommendation System** that suggests similar movies to a given title using various metadata features such as genre, overview, cast, crew, and keywords. The recommendations are based on the similarity between movies, allowing the system to offer personalized suggestions without the need for explicit user ratings or interaction history.

---

## 🛠️ Technologies and Tools Used

This project leverages the following tools and technologies:

* **Python**: Core language for data processing and model logic.
* **Pandas**: For data cleaning, transformation, and manipulation of movie metadata.
* **NumPy**: Enables efficient numerical operations and array handling.
* **Scikit-learn**: Used for TF-IDF vectorization and computing cosine similarity.
* **Natural Language Processing (NLP)**: Processes and vectorizes textual features like overviews, keywords, and genres.
* **Google Colab**: Supports interactive development and testing.
* **Matplotlib / Seaborn** *(optional)*: Helps visualize trends and explore data distributions.

---

## 📊 Dataset Features

The dataset contains metadata about movies with the following attributes:

* **Poster\_Link**: URL to the movie poster image.
* **Series\_Title**: Title of the movie.
* **Released\_Year**: The year the movie was released.
* **Certificate**: Age certification (e.g., PG, R).
* **Runtime**: Duration of the movie.
* **Genre**: Movie genres (e.g., Action, Comedy).
* **IMDB\_Rating**: Rating as per IMDb.
* **Overview**: Brief synopsis of the movie.
* **Meta\_score**: Metacritic score.
* **Director**: Name of the movie’s director.
* **Star1 - Star4**: Names of the top four cast members.
* **No\_of\_Votes**: Number of user votes on IMDb.
* **Gross**: Box office gross revenue.

---

## 🚀 How to Run

### ▶️ Run on Google Colab

1. Open the provided Colab notebook.
2. Upload the dataset.
3. Run the cells step-by-step.

### 🌐 Run with Streamlit (Optional)

1. Install Streamlit:

   ```bash
   pip install streamlit
   ```
2. Save the app script (e.g., `app.py`).
3. Run the app:

   ```bash
   streamlit run app.py
   ```

---

## 🔍 Sample Input/Output

* **Input Movie**: `The Godfather`
* **Recommended**:

  * Goodfellas
  * Scarface
  * The Departed
  * Pulp Fiction
  * Casino

---

## 📂 Repository Structure

```
├── imdb/data             # Movie dataset files 
├── notebook.ipynb        # Development and exploration notebook
├── app.py                # Streamlit web app
├── README.md             # Project documentation
```

---

## 📬 Contact

For queries or contributions, feel free to reach out.

---

> ⭐ Don't forget to give this repo a star if you found it useful!
