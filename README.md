# Collaborative-Filtering
This project uses collaborative filtering technique to calculate similarity between movies.

Run "calculate_similarity.py" first, it will calculate the similarity between every two movies.
The result will be store in "outcome\similarities.csv".

Then run "predict.py". It will sort "outcome\similarities.csv" by movie ID, and for each movie, it lists the 10 
other movies that are most similar with it. And the result will be stored in "outcome\Top_10.csv".

The result can be used to recommand movies to users. For example, a user watch movie A before, and we have calculated
the 10 movies that are most similar with movie A, then we can recommand these 10 movies to this user since she is likely
to be interested in them as well.
