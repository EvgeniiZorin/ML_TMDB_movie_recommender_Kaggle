# Overview

This is an exercise from the Udemy course `[2026] Machine Learning: Natural Language Processing (V2)`, lecture `18. (Interactive) Recommender Exercise Prompt`. 

- [Udemy course link](https://www.udemy.com/course/natural-language-processing-in-python/learn/lecture/28889574#overview)
- [Kaggle dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

Task: build a recommendation system so that when you are given a movie's title, you are given 5 most similar movies. 

Details:
- Query is "Scream 3", then recommend other movies based on this
- Get TF-IDF representation of this movie
- Compute similarity between Scream 3 and all other vectors
- Sort by similarity
- Print out the top 5 closest movies
- Try movies from other genres

# Models

- v1: recommendation based on vector similarity of query vector to vectors of other movies, with `overview` field processed by TF-IDF;
- v2: v1 but with more TF-IDF - vectorised fields, e.g. title, keywords, etc.
- v3: additionally incorporates numeric fields;
