# Movie-Recommendation-Engine
A recommendation engine for movies using collaborative filtering. Predicts movie ratings based on user similarity and generates top movie recommendations for users.

# Movie Recommendation Engine

## Overview
This repository contains a collaborative filtering-based movie recommendation engine. The engine predicts user movie ratings based on their similarity with other users and provides recommendations for movies they might enjoy.

## Dataset
- **Movies Dataset**: Contains movie information (`movieId`, `title`).
- **Rating Dataset**: Contains user ratings (`userId`, `movieId`, `rating`).

## Preprocessing
1. **Load Data**: Import and merge movie and ratings datasets.
2. **Explore Data**: Examine the number of users, movies, and the distribution of ratings.
3. **Sort Data**: Organize the dataset by `userId` and `movieId`.

## Recommendation Engine
1. **User-Movie Rating Matrix**: Construct a matrix with users as rows and movies as columns.
2. **Similarity Calculation**: Compute similarity between users using a correlation-based metric.
3. **Nearest Neighbors**: Identify similar users and predict ratings for unseen movies.
4. **Top N Recommendations**: Generate and sort movie recommendations for users.

## Usage
1. **Load Datasets**: Ensure you have the datasets available in the correct directory.
2. **Run the Code**: Execute the scripts to load data, compute similarities, and get recommendations.
3. **Get Recommendations**: Use the provided functions to find top N movie recommendations for a specific user.
