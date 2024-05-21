
# Movie Recommendation System 

## This is the final project for Data Mining and Advanced Statistical Methods in Business Applications Course

In this project, we aims to develop a movie recommendation system that leverages multiple recommendation techniques and a matrix factorization approach to address data sparsity. The project utilizes data from The-Movie-Dataset, a comprehensive resource for movie information.

### Approaches:

1. **Content-Based Filtering**: This approach recommends movies similar to those a user has enjoyed in the past. Movie attributes such as genre, director, actors, and keywords will be used to identify similar movies.

2. **Collaborative Filtering**: This approach identifies users with similar taste profiles and recommends movies enjoyed by those users. The system will analyze user-movie interaction data to find these patterns.

3. **Hybrid Filtering**: This approach combines content-based and collaborative filtering techniques to leverage the strengths of both methods. It aims to provide more robust and personalized recommendations.


### Model-based Recommneder Performance:

| No | Algorithm                | RMSE   | MAE   |
|----|--------------------------|--------|-------|
| 1  | Baseline Item-based CF   | 2.5511 | 2.2585|
| 2  | Baseline User-based CF   | 1.7188 | 1.3484|
| 3  | Baseline SVD             | 0.9041 | 0.6974|
| 4  | SVD++                    | 0.8986 | 0.6924|
| 5  | KNN Basic (user-based)   | 0.943  | 0.73  |
| 6  | KNN Mean (user-based)    | 0.918  | 0.705 |
