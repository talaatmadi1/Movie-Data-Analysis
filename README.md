# Movie Data Analysis Project (TMDB Dataset)

This project was developed as part of the **Introduction to Computer Programming (2024/2025)** course at **LUISS University**.  
It involves analyzing a subset of **The Movie Database (TMDB)** dataset using Python to extract insights about movies, genres, keywords, production companies, and countries.

---

## 🎯 Objective

The goal of this project is to practice data manipulation, file handling, and dictionary-based data structures in Python’s standard library.  
The project focuses on analyzing 5 CSV files containing information about 5000 movies, and answering specific analytical queries using Python.

---

## 📁 Dataset Description

The dataset consists of 5 CSV files, each containing structured data related to movies:

| File Name | Description |
|------------|--------------|
| `movies_table.csv` | Main file containing movie details (ID, title, budget, revenue, release date, popularity, language, runtime, votes, etc.). |
| `genres_table.csv` | Movie-genre pairs; each movie can have multiple genres. |
| `keywords_table.csv` | Movie-keyword pairs; each movie can have multiple keywords describing it. |
| `production_companies.csv` | Movie-production company pairs; each movie may involve multiple production companies. |
| `production_countries_table.csv` | Movie-country pairs; each movie may have multiple production countries. |

---

## 🧠 Queries Implemented

### Query 1 — Genre Rating Distribution
Calculates the distribution of movie ratings for each genre.  
Output: a pickle file (`query1.pkl`) containing a dictionary  
`{genre: {rating_range: count}}`.

### Query 2 — Average Keywords per Genre
Computes the average number of keywords associated with movies in each genre.  
Output: a pickle file (`query2.pkl`) containing  
`{genre: average_number_of_keywords}`.

### Query 3 — Top Production Companies per Genre
Identifies the most common production companies for each genre based on the number of movies produced.  
Output: a pickle file (`query3.pkl`) containing  
`{genre: [(company_name, count), ...]}` sorted in descending order.

---

## 🧩 Technologies Used

- **Python 3.12**
- **Standard Libraries only** (no external dependencies)
  - `csv`
  - `json`
  - `pickle`

---


