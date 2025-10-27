# Amazon-Music-Clustering

The Amazon Music Clustering Project aims to group similar songs together based on their musical features such as danceability, energy, loudness, acousticness, instrumentalness, tempo, and valence. By applying machine learning clustering techniques, this project helps understand the structure and patterns in music data — identifying which songs share similar characteristics and could belong to the same genre or mood group.

# Project Summary 

Objective:
To group Amazon Music songs based on their audio features such as danceability, energy, loudness, acousticness, and tempo using K-Means clustering.

Data Preprocessing:
The dataset was cleaned by checking for missing and duplicate values, and all numerical features were normalized using StandardScaler for accurate clustering.

Clustering Process:
The Elbow Method and Silhouette Score were used to determine the best number of clusters. The K-Means algorithm was applied to group songs with similar characteristics.

Results:
The songs were successfully divided into four clusters, such as danceable & energetic songs, acoustic songs, and instrumental tracks.
