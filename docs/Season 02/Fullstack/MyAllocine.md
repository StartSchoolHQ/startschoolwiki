---
sidebar_label: 'My Allocine'
sidebar_position: 6
---

# My Allocine

The sample database represents some of the data storage and retrieval about a movie related industry. Most of the people loves to watch movie, and for all of them we are providing a sample information about the movie related questions coming to their mind. This design of database will make it easier to the movie lovers to know the curiosities about the movies.

## 📝 Requirements

- **Uses specified tables**: actors, genres, directors, movies, movies_genres, movies_actors, directors_movies, reviews, movies_ratings_reviews.
- **Only queries array submitted**: Format ```requests[REQUEST_DESCRIPTION_1] = "SQL_REQUEST_1"```

## 🛠️ Useful resources for accomplishing this task

TODO

## 💡 Advice for completing the task
- last query in the requirements is wrong. To successfully pass test, you need to change the array key to what Gandalf expects there
  - In project requirements it is:
    ```bash 
    requests["Find all the actors who have not acted in any movie released between 1990 and 2000 (select only actor first name, last name, movie title and release year) sorted by actor ID)"]
    ```
  - But Gandalf expects this array key (note the ending part):
    ```bash
    requests["Find all the actors who have not acted in any movie between 1990 and 2000 (select only actor first name, last name, movie title and release year)"]
    ```
      