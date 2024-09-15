
Overview
This repo helps to explore relationships between budget, genre_ids, average vote score, and profits. The best movies for optimizing vote score and total profit are long, high budget, Action/SciFi or Action/Adventure movies. Animation/Adventure/Comedy movies also do very well according to data

Bussiness Problem
Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry. Your team is charged with exploring what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

The Data
The data we were given were pulled from several sources: Box Office Mojo (https://www.boxofficemojo.com), IMDB (https://www.imdb.com/interfaces/), Rotten Tomatoes (https://www.rottentomatoes.com), and The Movie Database (https://www.themoviedb.org/?language=en-US).

Questions to consider:
What is the distribution of movie budgets in the dataset?
How does the popularity of a movie relate to its budget and revenue?
Are there any trends in the release of movies over the years?
Which movie genres are the most profitable on average?
Which studios have produced the most successful movies in terms of revenue and profits?
Is there a correlation between the votecount and its revenue?
Sources of data
Box Office MojoLinks to an external site.
IMDBLinks to an external site.
Rotten TomatoesLinks to an external site.
TheMovieDBLinks to an external site.
The Numbers
Description of data
#numpy for high level mathematical functions and working with Arrays import numpy as np #pandas data manipulation and analysis for tablular data import pandas as pd #seaborn and matplotlib for data visualization import seaborn as sns import matplotlib.pyplot as plt %matplotlib inline

loading data
df=pd.read_csv("bom.movie_gross.csv.gz",index_col=0) df df_1 =pd.read_csv("tmdb.movies.csv.gz",index_col=0) df_1 df_2=pd.read_csv("tn.movie_budgets.csv.gz",index_col=0) df_2

cleaning data
cleaned(df) cleaned(df_1) cleaned(df_2)

merging of dtaframes
#merged_df = df_merge.merge(df_2, on='movie') #merged_df #df_gp_movie = df_merge.groupby('movie') #df_gp_movie.first()

reassign back to a dataframe object
#df_merged_movie = df_gp_movie.first() df_merged_movie

Visualizations
