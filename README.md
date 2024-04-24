# SC1015_Steam_Game_Analysis
This is a student project done by NTU students for course SC1015 
Our group choose a kaggle dataset about steam video games and their ratings to analyse the factors that contribute to the rating of steam video games.

# Project Summary
# Dataset
Our dataset is on steam games and contains the name, release date, developer and publisher of the game, rating, number of positive and negative reviews, total reviews, technologies used in creating the game, the all-time peak number of players of the game, and the last modification time of the game.
# Problem Statement
We want to help developers find out what they should consider in the development of a game to create a game that does well.
# Machine Learning Models
Linear Regression
Decision Tree
Random Forest
Text Mining
Sentiment Analysis
Support Vector Regressions
# Results
We drew the conclusion that the most likely factor to influence the rating of steam video games is the percentage of users who left a review (review_percentage).
The text mining model was also useful in discerning which themes were most popular in each genre of video game. Train and test accuracy were not high in all machine learning models. The better performing models where those that could effectively deal with mixed data, like multi-variate linear regression.

Possible reasons for the poor performing models include:
- There are other variables not found in this dataset that also affect rating of a game, such as the country where the game was developed / target audience of a game by age group.
- Not enough genres are considered, as the genres that were unknown were removed at the start of the analysis.


# Links
[Kaggle Dataset] (
[Video Presentation]
# Team Members
Allen Lu Zhao Quan
Kriti Raja
Zhao Qixian


| Team Member | Email |
| ------------- | ------------- |
|Allen Lu Zhao Quan|ALLE0002@e.ntu.edu.sg|
|Kriti Raja|kriti006@e.ntu.edu.sg|
|Zhao Qixian|qzhao010@e.ntu.edu.sg|

# Contributions
| Part | Name |
| ------------- | ------------- |
| Data Cleaning and Preparation | Allen, Qixian  |
| Visualisation and Exploratory Data Analysis  | Allen, Qixian, Kriti |
| Machine Learning Models  | Qixian, Kriti |
