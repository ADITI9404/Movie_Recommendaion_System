# 🎬 Movie Recommendation System

A **Movie Recommendation System** built using Python that recommends movies based on the movie selected by the user.

The system uses **content-based filtering** and a **similarity matrix** to find movies that are most similar to the user's selected movie.

## 🚀 Features

* 🔍 Search/select a movie from the available movie list
* 🎯 Recommends the **Top 5 similar movies**
* 🧠 Uses content-based recommendation
* 📊 Calculates similarity between movies
* 💻 Simple and interactive user interface using Streamlit
* ⚡ Fast recommendations using a pre-computed similarity matrix

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Streamlit**
* **Pickle**


> File names may differ depending on your project structure.

## ⚙️ How It Works

The recommendation system follows these basic steps:

1. Load the movie dataset.
2. Process the relevant movie information.
3. Convert movie features into numerical representations.
4. Calculate similarity between movies using a similarity technique.
5. Store the similarity matrix for faster recommendations.
6. When a user selects a movie, the system finds movies with the highest similarity scores.
7. The **Top 5 similar movies** are displayed.

### Recommendation Flow

```text
User selects a movie
        ↓
Find movie in dataset
        ↓
Get similarity scores
        ↓
Sort movies by similarity
        ↓
Select Top 5 movies
        ↓
Display recommendations
```

## 💻 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### 2. Navigate to the Project Folder

```bash
cd movie-recommendation-system
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📦 Requirements

Example `requirements.txt`:

```text
streamlit
pandas
numpy
scikit-learn
```

## 🎯 Example

If the user selects a movie such as:

```text
The Dark Knight
```

The system analyzes its similarity with other movies and returns the most similar movies as recommendations.

## 📌 Recommendation Approach

This project uses **content-based filtering**.

Movies are compared based on their available features, and a similarity score is calculated between them. Movies with higher similarity scores are considered better recommendations.

The similarity scores are sorted in descending order, and the top results are returned to the user.


---

⭐ If you find this project useful, consider giving the repository a star!
