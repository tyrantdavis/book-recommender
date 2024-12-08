# [Building a Book Recommender System](https://nbviewer.org/github/tyrantdavis/book-recommender/blob/master/books.ipynb)

Click the title for a project demo.

## Introduction
Recommender systems play a crucial role in various organizations by assisting users in making informed choices, while also helping companies boost their revenue. Creating a basic recommender system can be a quick and straightforward process. This project will develop a book recommendation system for Books’R’Us utilizing the Surprise library.

Books’R’Us is a well-known bookstore chain that offers a wide range of books to customers nationwide. With the recent launch of their website, they are eager to incorporate a book recommendation feature. To achieve this, the book review data collected from their site will be utilized, which has been organized into a Pandas DataFrame named book_ratings.

This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.

**Data Sources:**

- [Good Reads Ratings](https://raw.githubusercontent.com/tyrantdavis/datasets/refs/heads/main/goodreads_ratings.csv)


## Project Goals
By introducing a book recommender system, Books’R’Us seeks to provide personalized suggestions to its customers, making it easier for them to discover new reads that they are likely to enjoy. This initiative will not only improve customer satisfaction but also encourage more engagement with the platform.



#### Why use a recommender to make predictions?
Recommender systems are specialized algorithms designed to analyze data related to products and user preferences, helping users find the most suitable choices from a variety of options available to them. These systems play a crucial role in guiding users toward decisions that align with their tastes and needs.

Typically, these systems leverage machine learning methods to enhance their effectiveness. By analyzing patterns in user behavior and product characteristics, they can provide personalized suggestions that improve the overall user experience.

While the techniques employed may be similar across different supervised learning applications, the key distinction lies in their intended purpose. Recommender systems focus on solving the challenge of identifying the optimal action for a user among multiple alternatives, whereas supervised learning is primarily concerned with predicting specific outcomes based on labeled data.

## Data
A dataset of books containing 3500 records that can be used to train the machine-learning model has been found. 


## Conclusions
- The recommender model is highly performant, as indicated by its impressively low RMSE score.
- The model estimated a likelihood of 3.83, indicating a greater than average probability that the user would appreciate the book recommendation.
