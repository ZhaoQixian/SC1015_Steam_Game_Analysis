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
Our analysis revealed that the primary factor likely to influence the ratings of Steam video games is the review percentage, which is the proportion of users who leave a review. Additionally, we utilized text mining models to discern prevalent themes across different video game genres. This insight is particularly valuable for developers focusing on genre-specific game development, as it helps tailor content to meet the expectations and preferences of target audiences.

Further exploratory data analysis indicated that the technology used in game development significantly impacts game ratings. Therefore, developers should carefully select their technology platforms to enhance game performance and player satisfaction.

However, the accuracy levels in our machine learning models varied, with not all models achieving high train and test accuracies. The more successful models were those capable of handling mixed data types effectively. Models such as multivariate linear regression and random forest analysis stood out for their ability to integrate and analyze diverse datasets, leading to more reliable predictions of game ratings. These findings suggest that choosing the right analytical models is crucial for developers and analysts aiming to gain meaningful insights from complex and varied data in the video game industry.

Possible reasons for the poor performing models include:
- There are other variables not found in this dataset that also affect rating of a game, such as the country where the game was developed / target audience of a game by age group.
- Not enough genres are considered, as the genres that were unknown were removed at the start of the analysis.
- A lot of data was removed during the data cleaning process due to null values, which may have led to inaccurate analysis of effect of variables on rating of steam video games.
## Recommendations for Game Developers
For game developers aiming to enhance the success of their games, the analysis suggests a multi-pronged approach based on key insights from the data. First and foremost, the importance of positive reviews cannot be overstated; a higher percentage of positive feedback is strongly correlated with better game ratings. Developers should focus on quality and player satisfaction to foster positive reviews, potentially incorporating feedback mechanisms that encourage satisfied players to leave reviews.

Furthermore, leveraging the findings from text mining, it is evident that certain themes and keywords frequently associated with higher-rated games can be crucial. Developers should consider these popular themes when designing games, as they resonate well with the target audience. This might involve analyzing top-performing games to identify common elements that can be creatively incorporated into new projects.

Lastly, the analysis highlighted that specific genres, including Indie, Casual, Adventure, Action, and Simulation, tend to perform well. Developers should consider these genres when planning new games, especially if they align with their team’s expertise and market trends. Understanding the preferences of their target demographic and crafting games that mesh well with these insights can significantly influence a game's reception and success. Overall, an informed approach that combines an understanding of player reviews, thematic preferences, and genre trends will equip developers with a robust strategy to design and market games that are more likely to succeed in a competitive market.

## Links

[Kaggle Dataset](https://www.kaggle.com/datasets/whigmalwhim/steam-releases)
[Youtube Link to Presentation](https://www.youtube.com/watch?v=tVbijpN8ZHs)
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
