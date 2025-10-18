# 🎬 TMDB Movie Data Analysis using Pandas and APIs

## 📘 Project Overview
This project focuses on **extracting, cleaning, and analyzing movie data** from the **TMDB (The Movie Database)** API using **Python and Pandas**.  
It demonstrates how to handle real-world JSON-like data, normalize nested structures, clean invalid or missing data, and prepare it for analysis and visualization.

The goal is to:
- Clean raw TMDB data (with nested JSON objects).
- Extract meaningful fields (like genres, production companies, and spoken languages).
- Handle missing, duplicated, or inconsistent records.
- Prepare the dataset for further insights (e.g., revenue vs budget, genre trends, production analysis).

---

## 🧰 Technologies Used
- **Python 3.10+**
- **Pandas** – for data manipulation and cleaning
- **AST** (Abstract Syntax Trees) – for safely evaluating JSON-like strings
- **Jupyter Notebook / VS Code** – for interactive exploration
- **TMDB API** – source of movie data

---

## 📂 Project Structure

TMDB-Movie-Data-Analysis/
│
├── data/
│ ├── raw_data.json # Original movie data fetched from TMDB API
│ └── cleaned_data.csv # Processed and cleaned dataset (output)
│
├── notebooks/
│ └── tmdb_cleaning.ipynb # Jupyter notebook with all steps
│
├── scripts/
│ └── clean_tmdb_data.py # Python script for data cleaning
│
├── README.md # Project documentation (this file)
└── requirements.txt # Python dependencies

## 📂 Clone the Repository

- **git clone https://github.com/BoaduJnr/tmdb-movie-data-analysis-using-pandas-and-apis.git**


## Set Up a Virtual Environment
- **python -m venv .venv**
- **.venv\Scripts\activate**
- **install packages** (pip3 install <package>)
