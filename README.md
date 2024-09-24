![image](https://github.com/user-attachments/assets/46c0118a-c0c7-411d-b155-941e75ee28e6)

# MERCURIAL
Mercurial is an intelligent music recommendation app that uses cutting-edge machine learning algorithms to suggest incredible tracks to the user. By analyzing the music that the user likes on the app, Mercurial recommends similar tracks based on their vibe. This personalized approach to music discovery ensures that users are always discovering new and exciting music that they love.


DATASET
The "data.csv" file contains more than 160.000 songs collected from Spotify Web API. The dataset is from Spotify and contains 169k songs from the year 1921 to year 2020. The dataset contains information about tracks in form of features such as acousticness, danceability, speechiness, loudness, time stamp, etc.


The link to the dataset:
https://www.kaggle.com/datasets/ektanegi/spotifydata-19212020



KEY FEATURES
1. Algorithm –
Mercurial uses the Kmeans++ machine learning algorithm to cluster data points into groups based on their similarity. The algorithm is an improvement over the original K-means algorithm as it selects the initial centroids in a more intelligent way. The algorithm starts by selecting one random data point as the first centroid and then selects the next centroid from the remaining data points based on their distance from the first centroid.
This continues until all centroids are selected. The result is a set of centroids that are well-spaced, which in turn gives the user those marvelous recommendations. 


2. The Engine:-
The application uses HTML, JavaScript, and CSS for the base of a spectacular UI. Mercurial also incorporates several other popular libraries like Jquery, Anime.js and the Puppertino framework. Another framework that has been used in this project is the scroll lock for disabling the overflow. For detecting user swipe gestures Mercurial integrates the swiped events framework. When the user right swipe (Like) 3 or more songs, they can click the "recommend" button. Mercurial then analyzes the liked tracks and suggests 5 songs


3. Deployment:-
For the deployment part Mercurial uses Flask which is a popular Python web framework that makes it easy to create web applications. Flask is based on Werkzeug WSGI toolkit and Jinja2 template engine. Using the "GET" & "POST" methods Python can communicate back and forth with Javascript.

![image](https://github.com/user-attachments/assets/6d6361bb-cb53-4704-b1d2-756cb60ae230)



