Music Recommendation System
Overview

This repository contains code for a music recommendation system based on content-based filtering using MinMaxScaler and cosine similarity. The system suggests similar songs based on their musical features. 

Features

    • Feature Scaling: Utilizes MinMaxScaler to scale music properties to a defined range.
    • Cosine Similarity: Computes similarity scores between songs using cosine similarity of their 	             feature vectors.
    • Recommendation Generation: Provides recommendations for similar songs based on a given input song.

Requirements

    • Python 3.x
    • https://developer.spotify.com/
        ◦  Login to page
        ◦ Create an app
        ◦ Get Client ID and Client Secret
        ◦ 
Usage

    • Ensure Client ID and Client Secret for data collection are written correctly
    • Ensure playlist ID from the Spotify are written correctly
    • Ensure your dataset containing music properties (e.g., Danceability, Energy, Tempo) is formatted correctly and loaded into the system.
    • Modify the song_recommendations function or script to suit your dataset and requirements.
    • Run the system and provide a song name to receive similar song recommendations.

Files

    • Data Collection ipynb
        ◦ Consist with 4 parts because we ended up reaching the max request retries
    • data1, data2, data3, data4.csv files are saved based on Data Collection ipynb
    • Final Project.ipynb consist with Model Training and Visualizations
    • Survey Folder
        ◦ Contains the screenshots that we sent to friends asking which songs did you liked
        ◦ Responder Link: https://docs.google.com/forms/d/e/1FAIpQLSdugcoPpaUspQy0VeYdrjZ07YebJRB9jkKWquDPt7aK4orhVg/viewform?usp=sharing
    • User Data Comparison Visualizations
        ◦ Our StreamingHistory json file and converted to dataframe for visualizations

Credits
    • Created by Siyeon Park, Isabella Francesconi

