# movie-recommendation-engine
Movie recommendation based on genres, actors and directors using the cosine similarity measure.

The mentioned columns were extracted and converted into sparse matrices using the CountVectorizer class. After that, the recommender system was built using the cosine similarity measure and combining the results of each matrix. The get_recommendations definition takes a movie title as an input and provides 10 titles most similar to it.
