# Unsupervised-algorithms-final-project

## Description
This repository is part of the Final project for DTSA 5510 Unsupervised Algorithms in Machine Learning.

### Dataset Used
The dataset used for this project can be found [here](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset).

## Content
The Book-Crossing dataset comprises 3 files:

### Users
Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL-values.

### Books
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

### Ratings
Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

### Objective 
We have data related to books, users, and ratings. We will try to formulate and identify groups of books that are similar to each other based on features such as ratings, genres, or author styles. This can help in recommending similar books to users or in inventory categorization.

