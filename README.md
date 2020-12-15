# spark-movies
A movie recommendation program that utilizes PySpark


Source:

Movie API used: [The Movie Database API (TMDb)](https://developers.themoviedb.org/3/getting-started/introduction)


Instructions:


Utilizing the Movie API to get all the movie data

After fetching the movie data, use Spark to process all the JSON

Spark is used to display all movie suggestions in parallel to the user

Program takes place on a command line and uses can select from a menu of options (listed below)

Recommendation Service has 12 functions and an exit (to get out of the program)
1. search by name   (name of movies)
2. search by year   (year of movies)
3. search by ratings  (how good the movies are, higher the better)
4. search by genre  (category of movies)
5. popular movies   (most watched movies)
6. top rated      (highest value)
7. now playing    (currently in theathers)
8. upcoming       (future movies)
9. recommend movies   (which movies are best, based on watchlist)
10. recommend by year   (which movies are best in each year, based on watchlist)
11. recommend by genre  (which movies are best according to specific categories based on watchlist)
12. print watchlist    (showing all the movies one selects)
13. exit    (end of program)



