# Predicting song's populairty on spotify

## About

## Problem Definition

Independent artists struggle to predict Spotify song popularity, leading to various drawbacks:

1. As an independent artist, it is difficult to gauge the potential popularity of a new song before releasing it on Spotify
2. Without data on how previous songs have performed, it's hard to make informed decisions about what to release next
3. Even with data, it is challenging to interpret it, especially for artists without a background in data science or analytics.

With these problems, about 70% of indie artists generate less than $10,000 from their music annually, despite accounting for 41.4% of the music industry.

Problem Statment: Develop a predictive model to predict the popularity of a song on Spotify before its release.

This will allow independent artists to:

1. Make more informed decisions about which songs to release and how to allocate their time and resources.
2. Better negotiate deals with record labels, potentially leading to more opportunities and revenue.
3. Tailor their marketing strategies and promotional efforts to maximize the song's impact upon release.
4. Enables artists to identify strengths and weaknesses, facilitating artistic growth and improvement in future releases.

## Data Collection and Preperation

Raw Dataset used: https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks?select=tracks.csv

The DataPrepandCleaning notebook shows the cleaning and preparing process

## Exploratory Data Analysis / Visualisation

The EDA notebook shows the data analysis process where each attribute and its relationship with populairty were explored.
The analysis suggests that when evalauting popularity:

Non-negligible Factors:

1. Duration
2. Explicit
3. Release Year
4. Release Month
5. Danceability
6. Energy
7. Loudness
8. Acousticness
9. Instrumentalness

Negligble Factors:

1. Number of Artists
2. Key
3. Mode
4. Speechiness
5. Liveness
6. Valence
7. Tempo
8. Time_Signature

## Use of Machine Learning

The ML Models notebook shows how various ML models were used to predict populairty and the evaluation of these models.

## Models Used

1. Linear Regression
2. Random Forest
3. Decision Tree
4. KNN (Found in new technique folder)

## Final Insights

KNN algorithm gave us the best model to be used for prediction of popularity.

## Conclusion

Future Implementations:

- Web scraping and removing top artists from dataset to further target independent artists
- Going a step further and classifying songs by genre first and then evaluating each

Insights:

- Working with and cleaning a raw dataset to better address our problem statement
- Using techniques such as cross-validation to improve models
- Linking back model’s results to EDA to understand the workings of the model

## What did we learn from this project?

- Using clustering to analyze data
- Modeling Using KNN and Random Forest for prediction
- Cross Validation to reduce overfitting and error
- Feature Selection on Models to determine importance

## References

https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks?select=tracks.csv
https://www.hypebot.com/hypebot/2020/12/stats-facts-data-independent-artists-need-to-know.html
