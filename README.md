<div align="center">
  
# Movie Recommendation Systems 
</div>


<div align="center">
<img src="https://user-images.githubusercontent.com/69224996/96219766-614fb480-0f3c-11eb-8aed-4a7b4c882f12.png" >
</div>

<br /> 


<div align="justify">

The rapid growth of data collection has led to a new era of information. Data is being used to create more efficient systems and this is where Recommendation Systems come into play. Recommendation Systems are a type of information filtering systems as they improve the quality of search results and provides items that are more relevant to the search item or are realted to the search history of the user.

They are used to predict the rating or preference that a user would give to an item. Almost every major tech company has applied them in some form or the other: Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow. Moreover, companies like Netflix and Spotify depend highly on the effectiveness of their recommendation engines for their business and sucees.

There are mainly three types of recommender systems:

 - **Demographic Recommender:**
It offers generalized recommendations to every user, based on movie popularity. This system recommends the same movies with similar demographic features to all users and it does not give personalized recommendations to users.

- **Content-Based Recommender:**
It builds an engine that computes similarity between movies based on certain metrics (such as genre, director, description, actors, etc.) and suggests movies that are most similar to a particular movie that a user liked. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it. 

- **Collaborative Recommender:**
This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filtering is based on the idea that users similar to a particular user can be used to predict how much that particular user will like a particular product or service those users have used/experienced but that particular user has not.

In this notebook, we will use MovieLens Datasets (including tmdb_5000_credits, tmdb_5000_movies and ratings_small) and implement three recommendation algorithms including Demographic, Content-Based and Collaborative Filtering, and finally try to build an ensemble of these models to come up with our final Hybrid Recommendation System.



</div>

