Weekend Movie Trip
==============================

### Data Clustering - Project 3

Submitted by:
Mugdha Bajjuri

#### Blockbuster or art film?

This dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from [MovieLens](http://movielens.org), a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users between March 29, 1996 and September 24, 2018. This dataset was generated on September 26, 2018.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

The data are contained in the files 'links.csv', 'movies.csv', 'ratings.csv' and 'tags.csv'. More details about the contents and use of all these files follows.

## Exploratory Data Analysis

- Combining all datasets to create one single big dataframe
- Word cloud showing most tags given by the users, to analyze user feedback on the movies
- Dash drop down shows movies based on selected year and genre

## Clustering

This project is a movie recommendation model using **"K-means clustering"** and **"DBScan clustering"** models to recommend similar movies to the user. The two features extracted from the dataset are Average Movie Rating and tags of the movie given by various users.

- Label Enocding on tags column
- Elbow Method to determine number of clusters
- Selecting the number of clusters with Silhouette analysis on KMeans clustering
- K-Means Clustering model
- checking the results of K-Means Clustering model
- DBSCAN Clustering model
- Visualizing both DBScan and K-means models
