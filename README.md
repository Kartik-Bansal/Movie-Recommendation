# **Movie Recommendation**

Building a model to analyze the rating based on comments of people and also extracting the genre from the comments. Search for a genre and get the best movie out of it (i.e. best rating)

## **Data**

We collected our dataset by scrapping the comments from imdb by Selenium library.

## **Features**

Given a comment it can predict the rating out of it. Then it will try to categorize the movie in top 4 genres selected by people for the movie from the list:

- Action
- Adventure
- Anime
- Children
- Family
- Classic
- Comedy
- Documentaries
- Dramas
- Horror
- Musical
- Romantic
- Sci-Fi
- Biography
- Thrillers
- TV shows

## **Machine Learning**

The model was built on Keras and Tensorflow library and used GRU to learn word embeddings.
