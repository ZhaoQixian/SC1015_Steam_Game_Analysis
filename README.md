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
Sentiment Analysis
Support Vector Machine
Random Forest
# Results
Overall train and test accuracy was low despite trying various machine learning models. The better performing models where those that could effectively deal with mixed data, like decision trees and random forest. Although some conclusions could be drawn, such as "Games of the genre platform are more likely to also have higher global sales.", these conclusions hold less weight due to the low classification accuracies.
Possible reasons for the poor classifications include:
There are other variables not found in this dataset that better explain the distribution of global sales. (e.g. Developer type: AAA, indie etc.)
Genres provided are not specific enough to gather sufficient insight. (e.g. "Shooter" is a genre provided, but it can be divided into subcategories like first-person shooter or third-person shooter, which might help us get better results if, for example, there are more global sales for a first-person shooter.)
Genres provided do not consider intermingling of genres. (e.g. A "Platformer" often incooperates "Puzzle" elements, but in this dataset, games are only assigned one genre, so this is not considered.)
Not enough genres are considered. (e.g. Genres such as single-player and multiplayer are not included in the dataset)


# Links
[Kaggle Dataset] (https://www.kaggle.com/datasets/ibriiee/video-games-sales-dataset-2022-updated-extra-feat)
[Video Presentation]
# Team Members
Name
Email
Chong Geng Yang
gchong016@e.ntu.edu.sg
Jin Qingyang
JINQ0003@e.ntu.edu.sg
Li Zhiyuan
d220009@e.ntu.edu.sg

Contributions
Part
Name
Data Cleaning
Geng Yang


Qingyang


Zhiyuan
Exploratory Data Analysis
Geng Yang


Qingyang


Zhiyuan
Machine Learning Models
Qingyang


Zhiyuan
Additional Research
Geng Yang


Qingyang


