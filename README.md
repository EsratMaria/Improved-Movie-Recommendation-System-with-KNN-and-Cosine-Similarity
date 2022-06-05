# Recommendation System

Recommendation systems improve the quality of search results and provide elements that are more relevant to the search item or that are related to the search history of the user.
Recommendation systems are widely used to recommend movies, items, restaurants, places to visit, items to buy, etc.

## Types of recommendation System

  
- **Popularity Based:** It keeps a track of view counts for each movie/video and then lists movies based on views in descending order.

- **Content Based:** This type of recommendation system, takes in a movie that a user currently likes as input. Then it analyzes the contents of the movie to find out other movies which have similar content. Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.

- **Collaborative filtering:** In this category, the recommendations get filtered based on the collaboration between similar user’s preferences.

![](https://i0.wp.com/thecleverprogrammer.com/wp-content/uploads/2020/11/1-recommendation.png?resize=1024%2C627&ssl=1)


**In this repository,** I tried making a movie recommendation system that suggests relevant movies according to a user's interest and previously rated movies.

### Dataset

I am using the [**MovieLens**](https://www.kaggle.com/ayushimishra2809/movielens-dataset) dataset. 
The data consists of **105339** ratings applied over **10329** movies. 

The **movies.csv** dataset contains three columns:

    movieId: the ID of the movie
    title: movies title
    genres: movies genres

The **ratings.csv** dataset contains four columns:

    userId: the ID of the user who rated the movie.
    movieId: the ID of the movie
    ratings: ratings given by each user (from 0 to 5)
    Timstamp: The time the movie was rated.
    
The **csv** files can be found [here](https://github.com/EsratMaria/Improved-Movie-Recommendation-System-with-KNN-and-Cosine-Similarity/tree/master/data).

### Approaches Tried

- Deleting Unnecessary Columns
- Remove the NaN values from the dataset
- Combining the files and making a pivot table
- Data Transformations
- Data Cleaning
- Data Exploration and fetching detailed information, details are [here](https://github.com/EsratMaria/Improved-Movie-Recommendation-System-with-KNN-and-Cosine-Similarity/blob/master/User%20Rating%20Prediction%20%26%20Data%20Extraction.ipynb).

### Recommendation Strategies

- KNN (K- Nearest Neighbor)
- Cosine Similarity
- Popularity (most rated) based recommender

### References

- [1](https://www.kaggle.com/midouazerty/restaurant-recommendation-system-using-ml) & [2](https://www.kaggle.com/ayushimishra2809/movie-recommendation-system)
