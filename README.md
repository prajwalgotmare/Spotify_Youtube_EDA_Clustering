# Spotify and Youtube Song Data - EDA and Clustering
This repository contains the code and data for performing exploratory data analysis (EDA) and clustering on a dataset of songs from various artists worldwide.

![image](https://149695847.v2.pressablecdn.com/wp-content/uploads/2019/04/if_spotify_then_youtube-1024x538.png)

## About the Dataset
The dataset contains 26 variables for each of the songs collected from Spotify. Few variables are briefly described below:

Track: name of the song, as visible on the Spotify platform.
Artist: name of the artist.
Url_spotify: the Url of the song.
Album: the album in which the song is contained on Spotify.
Album_type: indicates if the song is released on Spotify as a single or contained in an album.
Uri: a Spotify link used to find the song through the API.
Etc

These data are heavily dependent on the time they were collected, which is in this case the 7th of February, 2023.

## Exploratory Data Analysis :

In the EDA notebook, we perform an analysis of the different variables in the dataset. We examine the distribution of each variable, look for correlations between variables, and visualize the results with different plots.

## Clustering :
In the clustering notebook, we use the k-means algorithm to cluster the songs in the dataset based on their musical features. We first perform data preprocessing and feature scaling and then apply the k-means algorithm with different numbers of clusters. We evaluate the quality of the clusters with the elbow method and silhouette score.

## Conclusion :
In conclusion, this dataset provides a rich collection of information on songs and their associated statistics on Spotify and YouTube. Through our exploratory data analysis, we gained insights into the distribution of various features and their correlations. We also identified the top artists and songs in the dataset based on their number of streams and views.

Furthermore, we applied clustering techniques to group the songs based on their audio features and identified distinct clusters. These clusters can be useful for recommending similar songs to users or for music genre classification.

Overall, this dataset can be valuable for researchers and music enthusiasts alike, and can be used for a variety of applications such as music recommendation systems, genre classification, and trend analysis.
