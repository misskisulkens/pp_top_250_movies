# top250movies
## Scraping TOP 250 Movies (IMDb Website) and Analyzing the Data

Hi all, that's a simple project I decided to work on so that my skills don't get rusty :)

The data was gathered from https://www.imdb.com/chart/top/.

To complete the project I'm using the following libraries:
* **requests**;
* **bs4**;
* and **pandas**.

The data that I gather for each movie is:

```
{"rank": int(movie_rank),
"name": str(movie_name),
"year": int(movie_year),
"rating": float(movie_rating),
"link": str(movie_link),
"main_genre": str(main_genre),
"genres": str(genres),
"description": str(description),
"picture_link": str(picture_link)}
```

More details can be found in the _file_ itself :)
