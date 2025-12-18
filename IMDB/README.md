# IMDB Data Analysis using SQLite & Python

## Overview
This project focuses on analyzing IMDB movie data using **SQLite as the database layer**
and **Python for data extraction and analysis**.  
The objective is to demonstrate how relational databases can be queried efficiently
and integrated with Python to derive meaningful insights from structured data.

---

## Problem Statement
IMDB datasets contain large volumes of structured movie-related information.
Efficient querying and analysis of such data requires a combination of
SQL expertise and data analysis skills.

This project aims to:
- Store and manage IMDB data using SQLite
- Execute complex SQL queries for data extraction
- Analyze and interpret results using Python

---

## Dataset
- IMDB movie dataset stored in a SQLite database
- Includes information such as:
  - Movie titles
  - Genres
  - Ratings
  - Release years
  - Votes / popularity metrics (if applicable)

> The dataset is stored locally in a SQLite database for efficient querying.

---

## Approach

1. **Database Integration**
   - Connected SQLite database with Python using `sqlite3`
   - Executed SQL queries directly from Python

2. **SQL Querying**
   - Filtering and aggregating movie data
   - Using joins, group by, and conditional queries
   - Extracting structured results for analysis

3. **Data Analysis**
   - Loaded query results into Pandas DataFrames
   - Performed exploratory analysis and insights generation
   - Analyzed trends in ratings, genres, and release years

---

## Key Analysis Performed
- Distribution of movie ratings
- Genre-wise movie analysis
- Year-wise trends in movie releases
- Identification of high-rated and popular movies

---

## Tools & Technologies
- **Python**
- **SQLite**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
