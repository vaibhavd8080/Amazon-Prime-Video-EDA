# Amazon Prime Video – Exploratory Data Analysis

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Amazon Prime Video content catalog.

The analysis uses information about movies and TV shows, including content type, release year, genres, production countries, runtime, IMDb ratings, IMDb votes, TMDB popularity, and TMDB ratings. A separate credits dataset is also used to analyze actors and directors associated with the titles.

## Business Objective

The main objective is to identify meaningful patterns and trends in the Amazon Prime Video catalog that can support content-related business decisions.

The analysis focuses on:

- Distribution of movies and TV shows
- Most represented genres
- Production-country representation
- Release trends over time
- IMDb and TMDB ratings
- Popularity and audience reception
- Actor and director participation
- Missing-value analysis and data quality

## Key Insights

- Movies form the majority of the Amazon Prime Video catalog.
- Drama and Comedy are among the most represented genres.
- The United States is the largest production country in the dataset, with India also having significant representation.
- The catalog contains a substantial amount of newer content.
- TV shows have higher average IMDb and TMDB ratings than movies in this dataset.
- IMDb and TMDB ratings show a positive relationship.
- Popularity and ratings should be evaluated separately because highly popular or highly voted titles do not necessarily have the highest ratings.
- Missing metadata, particularly age certification and rating-related information, provides an opportunity for improving data completeness.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Dataset

The project uses two datasets:

### Titles Dataset

Contains information about Amazon Prime Video titles, including:

- Title
- Content type
- Release year
- Age certification
- Runtime
- Genres
- Production countries
- Seasons
- IMDb score
- IMDb votes
- TMDB popularity
- TMDB score

### Credits Dataset

Contains information about people associated with the titles, including actors and directors.

## Project Structure

```text
Amazon-Prime-Video-EDA/
│
├── Amazon Prime Video - Exploratory Data Analysis.ipynb
├── README.md
│
└── data/
    ├── titles.csv
    └── credits.csv
