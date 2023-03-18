# Anime Recommendation system

![263296](https://user-images.githubusercontent.com/125176903/226091976-9842df10-2769-450a-965a-138fa2af6cb3.png)

Collaborative filtering and content-based filtering are two popular approaches to recommendation systems. Collaborative filtering utilizes the past behaviors and preferences of users to make recommendations for items, while content-based filtering relies on the attributes of items to generate recommendations.

In our project, we have integrated data from Myanimelist API, atleast with 20 million user data and 24000 anime details. To make recommendations, you have used the latent factor method, which is a type of collaborative filtering algorithm.

The latent factor method involves creating a matrix of users and items, where each cell represents the rating of a particular user for a particular item. This matrix is typically sparse, meaning that most of the cells are empty because most users have not rated most items.

The goal of the latent factor method is to factorize this matrix into two lower-dimensional matrices: one representing users and the other representing items. These matrices are called latent factors because they are not directly observable. Instead, they are inferred based on the ratings that are available in the original matrix.

Once these matrices are created, they can be used to predict the ratings that a user might give to an item that they have not yet rated. This is done by taking the dot product of the user and item matrices to obtain a predicted rating.

Overall, the latent factor method is a powerful technique for making personalized recommendations based on the past behavior of users. By inferring latent factors, it is able to overcome the sparsity of the data and generate accurate predictions for items that users have not yet rated. By combining this approach with content-based filtering, which utilizes the attributes of items, our project is able to provide a robust and comprehensive recommendation system for anime.
