# Movie Recommender System

Welcome to the Movie Recommender System project! This project focuses on building a content-based recommender system for suggesting movies based on their similarities. The model utilizes the Pandas, Numpy, ast, Scikit-learn, and Nltk libraries to process and analyze the movie dataset. The [TMDB 5000 movies](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv) dataset is used as the primary data source for training and evaluating the recommender system.

## Dataset Setup

To run the model on your local device, please follow these steps:

1. Download the dataset zip files from [TMDB 5000 movies](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv).
2. Unzip the downloaded files to extract the CSV dataset files.
3. Place the extracted CSV dataset files in the same parent folder as the `.ipynb` file.

Make sure that the directory structure looks like this:

project_folder/
* ├── Movie Recommender System.ipynb
* ├── dataset1.csv
* ├── dataset2.csv
* ├── ...


## Requirements

Before running the project, ensure that you have the necessary dependencies installed. To install the required libraries, run the following command:

```bash
pip install -r requirements.txt
```

This will automatically install the latest versions of the required libraries, including Pandas, Numpy, ast, Scikit-learn, and Nltk.

## Project Overview

The Movie Recommender System project employs a content-based approach to recommend movies to users. It leverages vectorization techniques to determine similarities between movies based on their tags. By analyzing the dataset and calculating the similarity scores, the model can suggest movies that are likely to be of interest to a particular user.
