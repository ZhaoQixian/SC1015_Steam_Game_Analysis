# SC1015_Steam_Game_Analysis
NTU AY2023/2024 Semester 2 SC1015 Group Project FDAC Team 1

Our group chose a kaggle dataset about steam video games and their ratings to analyse the factors that contribute to the rating of steam video games.

# Project Summary
## Dataset
Our dataset is on steam games and contains the name, release date, developer and publisher of the game, rating, number of positive and negative reviews, total reviews, technologies used in creating the game, the all-time peak number of players of the game, and the last modification time of the game.
## Problem Statement
We want to find out the relationships between different features of a game and it's rating, in order to determine which features a game developer should consider or focus on to create a game that does well in the steam games website.
## Machine Learning Models
Linear Regression   
Decision Tree   
Random Forest   
Text Mining   
Sentiment Analysis    
Support Vector Regressions
## Results
We drew the conclusion that the most likely factor to influence the rating of steam video games is the percentage of users who left a review (review_percentage). We also found that models such as the text mining model were useful in finding out which themes were most common in each genre of video games, which could also be useful in the development of games in a specific genre. Exploratory data analysis also showed us that the type of technology used to create these games affects it's rating, and hence developers should also consider this when deciding what type of technology to use in the creation of their games.

Train and test accuracy were not high in all machine learning models. The better performing models where those that could effectively deal with mixed data, like multi-variate linear regression and random forest analysis. 

Possible reasons for the poor performing models include:
- There are other variables not found in this dataset that also affect rating of a game, such as the country where the game was developed / target audience of a game by age group.
- Not enough genres are considered, as the genres that were unknown were removed at the start of the analysis.
- A lot of data was removed during the data cleaning process due to null values, which may have led to inaccurate analysis of effect of variables on rating of steam video games.


## Links

[Kaggle Dataset](https://www.kaggle.com/datasets/whigmalwhim/steam-releases)
## Team Members
| Team Member | Email |
| ------------- | ------------- |
|Allen Lu Zhao Quan|ALLE0002@e.ntu.edu.sg|
|Kriti Raja|kriti006@e.ntu.edu.sg|
|Zhao Qixian|qzhao010@e.ntu.edu.sg|

## Contributions
| Part | Name |
| ------------- | ------------- |
| Data Cleaning and Preparation | Allen, Qixian  |
| Visualisation and Exploratory Data Analysis  | Allen, Qixian, Kriti |
| Machine Learning Models  | Qixian, Kriti |
