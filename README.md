# Recommendations with IBM
# Table of Contents
1.	Installation
2.	Libraries Used
3.	Project Motivation
4.	Data
5.	Project Outline
6.	Licensing, Authors, and Acknowledgements
# Installation
No installations needed. Used libraries available via Anaconda package manager.
# Libraries used:
1.	Numpy
2.	Pandas
# Project Motivation
This project provided an opportunity to get exposure to the generation of recommenders. Involves the expansion of the understanding of Rank based filtering, Collaborative filtering, and SVD models for recommendations.
# Project Data
Provided by IBM in collaboration with Udacity.
# Project Outline
There are three components in this project.
1.	Exploratory Data Analysis
o	Getting to know the data and developing data understanding.
o	What is the distribution of how many articles a user interacts with in the dataset?
o	The number of unique articles that have an interaction with a user.
o	The number of unique articles in the dataset (whether they have any interactions or not).
o	The number of unique users in the dataset. (excluding null values)
o	The number of user-article interactions in the dataset.
2.	Rank Based Recommendations
o	Find the most popular articles simply based on the most interactions.
o	In the absence of ratings for any of the articles, assume the articles with the most interactions are the most popular.
o	These are then the articles we might recommend to new users (or anyone depending on what we know about them).
3.	User-User Based Collaborative Filtering
o	In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.
4.	Matrix Factorization
o	Using the user-item interactions, build out a matrix decomposition. Using decomposition, evaluate performance.
# Licensing, Authors, and Acknowledgements
•	Udacity


