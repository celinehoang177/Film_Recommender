# Film Recommender System Using Machine Learning

The Film Recommender System project is designed to recommend movies for users based on their preferences. The recommendation system is built using machine learning techniques and leverages diverse datasets, including:

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

As a passionate movie enthusiast, I often find myself spending a considerable amount of time searching for movies to watch. I also enjoy reading reviews to get a sense of how others perceive and feel about each film. However, there are times when I run out of movie options on Netflix, and I believe that many other movie lovers share this experience.

To address this challenge and to enhance the movie-watching experience, I embarked on creating a film recommender system. The goal is to compile all the valuable reviews and sentiments about each movie, offering audiences an insightful overview of each film. With this system, choosing my next favorite movie becomes easier, and I can enjoy quality time with my family and friends.

This project provides in-depth movie details such as summaries, genres, release dates, ratings, runtimes, top cast members, user reviews, and recommendations. To fetch these data, I utilized the TMDB API at https://www.themoviedb.org/documentation/api. Additionally, I performed web scraping using `beautifulsoup4` to extract user reviews from IMDb and conduct sentiment analysis on them.

In the data manipulation and preprocessing stages, I employed `pandas` and `numpy` to prepare the datasets. I've also developed machine learning pipelines, employing `CountVectorizer`, `cosine_similarity`, and `Collaborative Filtering`, to process text and compute cosine similarity. Furthermore, my sentiment analysis model, stored in `nlp_model.pkl`, helps categorize user reviews as positive or negative.
