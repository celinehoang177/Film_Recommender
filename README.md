# Film Recommender System Using Machine Learning 🎥 

Welcome to my Film Recommender System project! 🍿🎬 This project is designed to help you recommend movies based on your preferences. The recommendation system is built using machine learning techniques and leverages diverse datasets, including:

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

As a passionate movie enthusiast, I often find myself spending a considerable amount of time searching for movies to watch. I also enjoy reading reviews to get a sense of how others perceive and feel about each film. However, there are times when I run out of movie options on Netflix, and I believe that many other movie lovers share this experience.

To address this challenge and to enhance the movie-watching experience, I embarked on creating a film recommender system. The goal is to compile all the valuable reviews and sentiments about each movie, offering audiences an insightful overview of each film. With this system, choosing your next favorite movie becomes easier, and you can enjoy quality time with friends, family, and loved ones 👪.

This application provides in-depth movie details such as summaries, genres, release dates, ratings, runtimes, top cast members, user reviews, and recommendations. It's a one-stop solution for movie enthusiasts, making movie selection a breeze.

To fetch these data, I utilized the TMDB API at https://www.themoviedb.org/documentation/api. Additionally, I performed web scraping using `beautifulsoup4` to extract user reviews from IMDb and conduct sentiment analysis on them.

In the data manipulation and preprocessing stages, I employed pandas and numpy to prepare the datasets. I've also developed machine learning pipelines, employing CountVectorizer and cosine_similarity, to process text and compute cosine similarity. Furthermore, my sentiment analysis model, stored in nlp_model.pkl, helps categorize user reviews as positive or negative.

## Getting Started

To run this project and explore the Film Recommender System, please follow these steps:

1. Start by cloning this repository to your local system.
2. Download all the required libraries with the command `pip install -r libraries.txt`.
3. In the `data_preprocessing 3.ipynb` and `data_preprocessing 4.ipynb` files, replace the API key in `tmdb.api_key` with your actual API key.
4. Open your terminal or command prompt from your project directory and run the `main.py` file with the following command: `python main.py`.
5. Hurray! You're now ready to explore the Netflix Film Recommender System and discover your next favorite movies.

Enjoy your cinematic journey, and happy movie hunting! 🍿📽️
