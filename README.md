# (Internet Movie Database (IMDB) movie Exploration)
## by (Ayodele Ayodeji Fortunate)

## Background Information on the Ford GoBike System Dataset

This dataset includes information about Internet Movie Database (IMDB) movie.
The data consists of information regarding 10,000 movies collected from The Movie Database (IMDb) including user ratings and revenue among others as we see in the variable description bellow. The dataset can be found in the [here](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems).

**Features Decription**

The dataset consists of almost 10866 rows and 21 columns:

In this project, I will be analysing IMDB movie dataset that contains information about 10,000 movies collected from The Movie Database (IMDb), including user ratings and revenue.

* id: Movie identification number
* tmbd_id: Internet movie database identification number for the movie 
* popularity: How viral the movie went
* budget: An estimate income and expendicture for the movie for a particular year
* revenue: Income generated from the movie for a particular year
* original_title: The title name of a particular movie
* cast: People who featured in the movie
* homepage: A page on the website where the movie was found
* director: The director of the movie
* tagline: A short text describing a dramatic (catchy and enticing short phrases) thought of each movie
* keywords: Description of notable object, concept, style or action that takes place in the movie.
* overviews: A brief summary of the movie
* runtime: The duration of the movie
* genres: classification of different categories of movies
* production_companies:Companies that produced the movie
* release_date: Movie released date
* vote_count: Movie rating
* vote_average:Movie rating average
* released_year:The particular year the movie is released

#### Few modifications done on the dataset
After assessing the imdb movie dataset, I discovered that the dataset has a total of 10866 rows and 21 columns. 9 total variables with null values and 1 duplicate. Moreover, the variables are in their exact datatypes

Here are the few modifications done on the dataset:

- The null values
- Duplicate values
- Strings seprated with delimeter (|) in some necessary variables consistent with my analysis

#### Question(s) for Analysis
1. Which genre are most popular from year to year?
2. which director has the highest movie popularity and what year?
3. what movie, production company has the highest revenue and what year?

## Summary of Findings

* The year range of the imdb-movie dataset in consideration was from 1961 to 2015
* More Popularity of 0 to about 3.4 are more in the imdb-movie dataframe
* Most of the imdb-movies were released between the year 2002 and 2015
* Most of the imdb-movies released have runtime ranging from 90 to 100
* It was observed that the year of release has strong correlation with genres.

> Using pandas groupby approach to group the genres and the maximum population I was able to find out total of 4 genres with the highest popularity from year to year with same popularity value of 32.985763. The 4 genres include Action, Adventure, Science fiction and Thriller.

> Same approach was used to filter the director who has the highest movie popularity and corresponding year. The director who has the highest popular movie was Colin Trevorrow with popularity rating of 32.985763. The movie was released in the year 2015, with the original title 'Jurassic World'.

> In conclusion, in an attempt to find out what movie, production company has the highest revenue and the corresponding year, It was observed that release_year has a strong positive correlation with revenue. There are more revenue between the year 2000 and 2015. It was also observed that popularity has a positive correlation with revenue. There are more revenue between popularity of 0 to about 6. However, based on my analysis, Avatar has the highest revenue of #2,781,505,847 in the year 2009 and for the record, it was the highest from year 1961 to 2015. The movie(Avatar) was produced by 4 movie production companies namely;

* Ingenious Film Partners
* Dune Entertainment
* Twentieth Century Fox Film Corporation
* Lightstorm Entertainment.

The 4 companies all made the production in the year 2009 with same revenue of #2,781,505,847

## Key Insights for Presentation

For the presentation, I will start by introducing the distribution of popularity and released year and the correlation between genre and popularity. Afterwards, I will be displaying the 3 questions for analysis stated above i.e most popular genre from year to year, follow by director with highest movie popularity and year of production and finally,movie, production company that has the highest revenue and the corresponding year. All done by using bar charts and scatter plots.

### Limitation:

> I could not plot a bar chart representation for all the samples in the dataframe in relation with my analysis question due to large dataframe.