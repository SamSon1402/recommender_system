# Recommend System Project

This project is a Python-based movie recommendation system. It processes movie data, including genres, keywords, cast, and crew information, computes similarity between movies, and provides recommendations based on a given movie title.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

The project utilizes movie metadata from the TMDb dataset to recommend similar movies based on user input. It computes similarity between movies using their attributes and provides recommendations accordingly.

## Installation

To install and run the project, follow these steps:

1. Load the dataset using this [link](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv).
2. Download the dataset files: `credits.csv` and `movies.csv`.
3. Run the following command from the terminal to install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. After installing the dependencies, use the following command to run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

## Usage

Once the Streamlit application is running, you can interact with it by typing the name of a movie you'd like a recommendation for. Click on the "Recommend" button to receive the top 5 similar movies.

![Screenshot](https://github.com/SamSon1402/recommender_system/assets/115778428/7bdfb268-fb6d-4518-b611-f5b862af2d97)

## License

I want to express my gratitude to [Travis Bell](https://www.linkedin.com/in/travisbell/?originalSubdomain=ca) for providing me with the API. Without his contribution, this project would not have been possible.
