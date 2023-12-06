# Introduction to Movie Recommendation Systems in Python

This article provides an introduction to recommendation systems in Python using machine learning, with a focus on collaborative filtering and the practical implementation of movie recommendations. The code utilizes the MovieLens dataset, and the steps are detailed in a Jupyter Notebook available [here](https://colab.research.google.com/github/Rajora0/ML_SYS_RECOMENDACAO/blob/main/ML_intro_a_sistemas_de_recomenda%C3%A7%C3%A3o_em_Python.ipynb).

## Loading and Preparing Data

The process begins by mounting Google Drive to access the MovieLens dataset. The notebook then downloads, unzips, and organizes the data, checking the contents of the specified directory.

## Exploratory Data Analysis

The loaded data includes information about movies and user ratings. Basic statistics and information are provided, offering insights into the dataset.

## Recommendations Based on Popularity

The notebook generates recommendations based on two criteria: total number of votes and average ratings. Movies with fewer than 50 votes are filtered out to ensure robust recommendations.

## Genre-Based Recommendation

Exploring genre-based recommendations, the notebook suggests movies with similar genres to those already watched by the user, enhancing the personalization of recommendations.

## Collaborative Filtering

Introduction to collaborative filtering involves calculating distances between users to find similar ones. Recommendations are generated based on the preferences of users who exhibit similar watching patterns.

## K-Nearest Neighbors (KNN) Implementation

The notebook delves into KNN, implementing it for movie recommendations. The code calculates distances between users, identifying the nearest neighbors and suggesting movies based on their preferences.

## Refining the KNN Implementation

The final part of the notebook refines the KNN implementation. Users can now customize the number of nearest neighbors and the quantity of movie recommendations, providing a more personalized and flexible recommendation system.

## Conclusion

This article serves as a practical guide to understanding and implementing recommendation systems, specifically collaborative filtering using KNN. By leveraging the MovieLens dataset, the code demonstrates how to provide personalized movie recommendations based on user preferences and similar user behavior. This introduction sets the foundation for further exploration into the field of recommendation systems and collaborative filtering in Python.
