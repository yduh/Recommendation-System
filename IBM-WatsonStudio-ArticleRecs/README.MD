# Recommendations with IBM
For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, 
and make recommendations to them about new articles we think they will like. 

## Overview of the data
Below is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

![alt text](https://github.com/yduh/Recommendation-System/blob/main/IBM-WatsonStudio-ArticleRecs/screen-shot-2018-09-17-at-3.40.30-pm.png)

Though the dashboard is just showing the newest articles, 
you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, we will perform a study using the data available on the IBM Watson Studio platform.

## Approaches performed
This project is devided into the following studies and tasks:

1. Rank-Based Recommendations: Recommend most popular articles based on the highest user-article interactions
2. User-User Collaborative Filtering: Make personal recommendation to each users by recommending unseen articles that were viewed by similar users
3. Content Based Recommendations: With NLP, recommend articles that are similar in content to a given article
4. Matrix Factorization: Use SVD to find new articles that a user will like to read


## File Description
1. Recommendations_with_IBM.ipynb: Contains the implemented recommendation techniques
