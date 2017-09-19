# Movie-Recommender-System
In use project, I used Netflix data to recommend movies which are quite similar according to the movies they watched and rated.
User Collaborative Filtering algorithm is used for this recommender system because the number of users weighs more than number of products. From the NetFlix input file, a user rating matrix was built to represent that which movies were related. Also a co-occurrence matrix was created to represent the relationship between different movies. Then user rating matrix and co-occurence matrix were multiplied to get a merged recommendeder list for users.

In this project, 4 MapReduce jobs were used do matrix multiplication. 

