# Hackathon in R

## Introduction 
The dataset contains [features](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/) of songs for a certain user collected on Spotify. The goal of this project was to predict if the user will like a track or not based on what he usually likes. We have been ranked based on our model accuracy between others students on Kaggle.<br> 
All songs are labeled in the column target: “1” means the user likes it while “0” means he does not.<br>
There is 16 columns in the dataset : The three latest describe the song with its name, the author and if it has been liked. The others are the features with which we will construct our model:<br>
<br>
 - acousticness.
 - danceability.
 - duration_ms.
 - energy.
 - instrumentalness.
 - key.
 - liveness.
 - loudness.
 - mode.
 - speechiness.
 - tempo.
 - time_signature.
 - valence.

[Here](https://www.kaggle.com/c/hackathon-machine-learning-65415321065432156413206/leaderboard) is the result of the competition : we finished 1st in a tie with an accuracy of 82% (IJK Team).
 