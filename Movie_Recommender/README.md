# Movie Recommender
Recommender systems typically fit into two categories: 
1. Content-based systems
2. Collaborative filtering systems

#### Content-Based Movie Recommendation Systems
Content-based methods are based on the similarity of movie attributes. Using this type of recommender system, if a user watches one movie, similar movies are recommended.
Input for building a content-based recommender system is movie attributes.
For Eg: If a user watches a action movie starring Robert Downey Jr., the system will recommend them movies in the same genre or starring the same actor, or both.

#### B) Collaborative Filtering Movie Recommendation Systems
Collaborative filtering systems are based on past interactions between users and movies. 
Input for a collaborative filtering system is made up of past data of user interactions with the movies they watch.
For Eg: If user A watches Movie_1, Movie_2, and Movie_3, and user B watches Movie_1, Movie_3, Movie_4, we recommend Movie_1 and Movie_3 to a similar user C. 

There are two major different approaches to collaborative filtering :
1. Item based - Item based filtering uses similarity between the items to determine whether a user would like it or not
2. User based - User based filtering finds users with similar consumption patterns as yourself and gives you the content that these similar users found  interesting.


#### Project implementation and workflow
Following are the subtasks of the project:
1. Importing libraries
2. Loading data
3. Checking for duplicate data
4. Analysing duplicate movie data
5. Item-based collaborative recommender - It calculates cosine similarity between movies. 
6. Item and Genre-based recommender - This will first find movies with similar genres and then select the best rating similarities.
7. User-Based Recommender: This calculates the mean score for each movie considering their rating.
8. Recommender System


