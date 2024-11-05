# Movie Recommendation System

This repository contains a movie recommendation system built using Python, Pandas, and scikit-learn. The system analyzes user preferences and suggests similar movies based on various features such as keywords, cast, genres, and director.

## Author Credit

This implementation is based on a foundational algorithm by codeheroku, which has been adapted and enhanced for this project.

## Features

- **Cosine Similarity**: Utilizes cosine similarity to recommend similar movies based on user input.
- **Data Processing**: Efficiently processes a dataset of over 10,000 movies using Pandas.
- **User-Friendly Output**: Displays a list of recommended movies based on user-selected titles.

## Installation

1. **Clone the repository**:
    ```
    git clone https://github.com/johntmvu/movie-recommender
    cd movie-recommender
    ```

2. **Install dependencies**:
    Make sure Python is installed, then install the required libraries with:
    ```
    pip install pandas scikit-learn numpy
    ```

3. **Prepare the Dataset**:
    Ensure you have a CSV file named `movie_dataset.csv` in the same directory as the script. This file should contain the relevant movie data.

## Usage

Run the following command to start the recommendation system:

```
python movie_recommender_completed.py
