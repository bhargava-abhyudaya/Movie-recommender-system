# Movie-recommender-system
# Algorithm For Recommendation
The Recommendations are made by computing similarity scores for movies using consine simarity. For each movie tags are created by combining various details like genre of the movie, title, top cast, director and then they are converted to vectors using which similarity matrix is formed. Then for any searched movie the movies with the largest similarity score with it are sorted and then recommended.

# Cosine Similarity
![image](https://github.com/bhargava-abhyudaya/Movie-recommender-system/assets/100035845/2f228447-9689-499c-9096-0a1e037f40d4)

# Files in the repository
1) Dataset.zip - It is archived file of the original database as obtained from TMDB
2) dataProcessing.ipynb - This jupyter notebook processes the original data and stores it into a file named 'movies_final.csv'
3) movies_final.csv - The processed dataset used for sentiment analysis
4) sentimentAnalysis.ipynb - Python code to train the machine learning model and recommend the movies

# References 
1) TMDB's Dataset : https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
2) Cosine Similarity : https://www.machinelearningplus.com/nlp/cosine-similarity/

# Example
![image](https://github.com/bhargava-abhyudaya/Movie-recommender-system/assets/100035845/eb7101c1-4c54-488d-899b-398d6aaba31b)

This is the example of the movies recommended by the system
