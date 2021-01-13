# Recommendation-System

There are two folders, `Movie-Tweetings` contains jupyter notebooks that I used in learning on an example of movie recommendation system. `IBM-Watson-Recomm-Engine` is the project that it analyze the interactions users have with articles on the IBM Watson Studio platform and make recommendation to them about new articles.   

## The 3 main branches 
1. Knowledge Based ([notebook1](https://github.com/yduh/Recommendation-System/blob/main/Movie-Tweetings/Introduction%20to%20the%20Recommendation%20Data.ipynb), [notebook2](https://github.com/yduh/Recommendation-System/blob/main/Movie-Tweetings/Most_Popular_Recommendations.ipynb)) : rare purchases (ex: car, house, luxury sell), look at the current trend or popularity 
2. Content Based ([notebook](https://github.com/yduh/Recommendation-System/blob/main/Movie-Tweetings/Content%20Based%20Recommendations.ipynb)) : use the items' content tags, act like an agent
3. Collaborative Filtering Based : use the interactions between users and items
  - Neighborhood based ([notebook](https://github.com/yduh/Recommendation-System/blob/main/Movie-Tweetings/Collaborative%20Filtering.ipynb)) - adopting the similar users' perference on them.
  - Model based (notebook)
     
#### Identifying neighborhoods ([notebook](https://github.com/yduh/Recommendation-System/blob/main/Movie-Tweetings/Measuring%20Similarity.ipynb))
 - similarity metrics [-1, 1], 1 is the most closest
    * Pearson's correlation coefficient
    * Spearman's correlation coefficient
    * Kendall's Tau
 - distance metrics [0, 1], 0 is the most closest
    * Euclidean distance
    * Manhattan distance
 

## Business cases for recommendations
1. Relevance : the focus of discussion in the above 3 branches
2. Novelty
3. Serendipity 
4. Increased Diversity
