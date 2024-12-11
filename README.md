# Anime Recommendation System

## Overview
This project implements an Anime Recommendation System using cosine similarity. It leverages anime features like genres, ratings, and broadcast types to suggest similar anime titles. The system aims to provide personalized recommendations based on the similarity between anime.

## Table of Contents

* Project Description
* Dataset Details
* Technologies Used
* Steps Performed
* Results and Insights
* Future Enhancements

## Project Description
The dataset includes information about various anime titles, their genres, ratings, and more. This recommendation system:

1. Computes similarity scores between anime using cosine similarity.
2. Recommends anime similar to a given title based on these scores.
3. Evaluates the system's performance using metrics like precision, recall, and F1-score.

## Dataset Details
* Dataset Features:
* Unique ID for each anime.
* Title and broadcast type (e.g., TV, OVA).
* Genre and number of episodes.
* Average ratings and number of users who rated each anime.
* Community membership count for each anime.

## Technologies Used
* Programming Language: Python
* Libraries:
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Steps Performed
1. Data Preprocessing:

Loaded the dataset into a Pandas DataFrame.
Handled missing values appropriately.
Explored the dataset to understand its structure.

2. Feature Extraction:

Selected key features like genres and user ratings for similarity computation.
Encoded categorical features into numerical formats.
Normalized numerical features to ensure consistency.

3. Recommendation System:

Computed cosine similarity between anime titles based on selected features.
Designed a function to recommend similar anime based on similarity scores.
Experimented with threshold values to adjust recommendation list size.

4. Evaluation:

Split the dataset into training and testing sets.
Evaluated recommendations using precision, recall, and F1-score.
Analyzed areas for improvement based on evaluation results.

## Results and Insights
* Key Findings:
* similar anime were effectively recommended based on features like genres and ratings.
* Higher similarity thresholds led to more precise but fewer recommendations.
* Evaluation:
* Achieved [specific performance metrics, if available] on the test dataset.

## Future Enhancements
* Integrate user-based and item-based collaborative filtering techniques for more personalized recommendations.
* Use advanced similarity metrics like Pearson correlation or hybrid approaches.
* Build a user-friendly interface for better usability.
