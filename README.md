# Content-Based Recommender System with Streamlit

This is a Content-Based Recommender System built using Streamlit, a Python library for creating interactive web applications, and PyCharm as the development environment. The recommender system is designed to provide movie recommendations based on user preferences, using the TMDB Movie Metadata dataset from Kaggle.

## Table of Contents

- [Introduction]
- [Features]
- [Installation]
- [Usage]
- [Data]
- [Demo]

## Introduction

Content-based recommender systems recommend items to users based on the characteristics of the items and a profile of the user's preferences. In this project, we have implemented a content-based movie recommender system using the TMDB Movie Metadata dataset from Kaggle. Users can input their preferences for movie genres, release year, and vote average, and the system will provide a list of recommended movies based on those preferences.

## Features

- Interactive user interface built with Streamlit.
- Content-based movie recommendations.
- Filtering options based on movie genre, release year, and vote average.
- User-friendly and easy to use.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/aavishkarkedari/Content-Based-Recommender-System-with-streamlit.git
cd Content-Based-Recommender-System-with-streamlit
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle using the following link:
   [TMDB Movie Metadata dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

4. Place the downloaded `tmdb_5000_movies.csv` file in the project directory.

5. Run the Streamlit app:

```bash
streamlit run app.py
```

## Usage

1. Open your web browser and go to the URL displayed in your terminal when you run the Streamlit app.
2. Use the user interface to input your preferences for movie genre, release year, and vote average.
3. Click the "Get Recommendations" button to see a list of recommended movies based on your preferences.

## Data

The dataset used for this project is the TMDB Movie Metadata dataset from Kaggle. You can download it using the following link:
[TMDB Movie Metadata dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

## Demo

Here is a live demo of the recommender system: 

