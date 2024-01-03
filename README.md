*TMDB Movie Recommendation System*

Overview

This repository contains a movie recommendation system built using the TMDb (The Movie Database) dataset. The recommendation model employs the CountVectorizer technique to analyze the movie's plot descriptions and provide personalized movie suggestions. The model is then saved using the pickle library for later use.

Dataset

The dataset used in this project is sourced from TMDb and includes various information about movies, such as title, genres, overview (plot description), release date, and more.

Project Structure

The project is organized as follows:

data: Contains the TMDb movie dataset in CSV format.
notebooks: Jupyter notebooks for data exploration, preprocessing, and model development.
src: Python scripts for utility functions, data processing, and model training.
models: The recommendation model saved using pickle.
requirements.txt: List of dependencies needed to run the project.

Exploratory Data Analysis

The notebooks in the 'notebooks' directory cover the exploratory data analysis process, including visualizations, statistical summaries, and insights into the TMDb movie dataset.

Data Preprocessing

The 'src' directory contains Python scripts for data preprocessing, including handling missing values, encoding categorical variables, and preparing the plot descriptions for vectorization.

Recommendation Model Development

The recommendation model is developed using the CountVectorizer technique to convert the plot descriptions into numerical representations. The model training and evaluation code can be found in the 'notebooks' and 'src' directories.

Model Evaluation

The performance of the recommendation model is assessed using relevant metrics, and the results are discussed in the notebooks.

Model Deployment

The trained model is saved in the 'models' directory using the pickle library. This allows for easy integration and deployment into other applications for real-time movie recommendations.

Conclusion

The movie recommendation system utilizing CountVectorizer and pickle has been successfully implemented and evaluated.
