# Recommender System

Recommender systems encompass a class of techniques and algorithms that can suggest “relevant” items to users. They predict future behavior based on past data through a multitude of techniques including matrix factorization.

#### Application of Recommender System
Following are some applications of recommender system:
1. Content recommendation by YouTube
2. New friend recommendation by Facebook 
3. Product recommendation by Amazon

#### Types of Recommender System
Machine learning algorithms in recommender systems typically fit into two categories: 
1. Collaborative filtering systems
2. Content-based systems 

Modern recommender systems combine both approaches.

#### Collaborative filtering methods
Collaborative methods are based on the past transactions history (“user-item interactions matrix”) of a user. They analyse these items in order to produce new recommendations.
The main idea is that these past user-item interactions are sufficient to detect similar users and/or similar items and make predictions based on these estimated proximities.

Collaborative filtering algorithms is divided into two sub-categories:
1. Memory based approach - Memory based approaches directly works with past transaction history.They are based on nearest neighbours search
2. Model based approach - Model based approaches assume an underlying “generative” model that explains the user-item interactions and try to discover it in order to make new predictions.

#### Content based methods
Content based approaches uses information about users and/or items along with the transaction history. This additional information can be - age, gender, location, etc.
The idea of content based methods is to try to build a model, based on the available “features”, that explain the observed transactions.




