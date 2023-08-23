# Movie Data Analysis Project
This project involves analyzing a dataset containing information about movies, such as their titles, ratings, genres, production details, and more. The primary goal of this analysis is to gain insights into the movie industry, understand trends, and explore relationships between various attributes.

### Table of Content
- Introduction
- Data Overview
- Analsysis Step
- Observations & Conclusions

### Introduction
The movie data analysis project focuses on exploring a dataset of movies to uncover patterns, trends, and relationships within the film industry. The project utilizes Python programming language and several data analysis libraries such as Pandas, Matplotlib, and Seaborn.

### Data Overview
The dataset used in this project contains information about various movies, including attributes like titles, ratings, release dates, directors, genres, and production companies. Some of the key attributes include:

- Rotten Tomatoes link
- Movie title
- Movie information
- Critics' consensus
- Content rating
- Genres
- Directors
- Authors
- Actors
- Release dates
- Ratings (Tomatometer and Audience)
- Audience counts
- Production company

### Analysis Step
The project's analysis involves the following steps:

1. Data Loading: Reading the dataset using Pandas.
2. Data Cleaning: Handling missing values by dropping rows with null values.
3. Exploratory Data Analysis (EDA): Visualizing the data to gain insights.
  - Creating histograms and distributions for attributes like runtime, ratings, and counts.
  - Analyzing the distribution of content ratings, comparing Tomatometer and Audience ratings, and observing movie release trends over the years.
  - Exploring correlations between attributes using correlation matrices and heatmaps.
  - Investigating top directors and actors with the highest movie counts.
  - Studying movie counts based on runtime categories and content ratings.
  - Analyzing top production companies and genres.

### Observations & Conclusions

#### Audience vs. Critics Rating
- Rotten and Fresh critics' ratings have a very similar distribution.
- Audience tends to rate movies more positively compared to critics, indicating that audiences are generally "nicer" in their evaluations.
#### Movie Runtimes
- The majority of movies have an average runtime of around 106 minutes.
- Approximately 75% of movies have a runtime of 116 minutes or less.
#### Content Ratings and Movie Production
- A significant number of movies are rated either R or PG-13.
- A surge in movie production occurred in the 2000s, indicating a boost in the industry.
- During the 2008-2012 period, possibly due to the economic crisis, there was a considerable decrease in movie productions. Similar trends were observed in 2020, likely attributed to the impact of COVID-19.
#### Correlations and Paterns
- There are no standout correlations among the analyzed attributes. One interesting observation is how the notion of longer movies not resonating well with audiences doesn't hold true.
- Release Year and Top Critics Count exhibit a moderate correlation, possibly due to more journalists shifting to careers as critics as the industry grows.
- Surprisingly, there's a lack of correlation between Release Year and Runtime, suggesting that movies' runtime trends are not closely linked to the passage of time.
#### Directors and Actors
- Among the top directors, there's no female director who ranks among the top 10 in terms of movie counts.
- When it comes to top actors, only three women—Sandra Bullock, Meryl Streep, and Nicole Kidman—have appeared in more than 20 movies.
- Clint Eastwood stands out as a multi-talented individual who has acted in 28 feature films and directed a remarkable 50 films.
#### Movie Lenght Probabilities
- There's a 55.16% probability that a movie will have a "Long" runtime. Additionally, there's a 44.54% probability that a movie will have a "Medium Long" runtime.
- There's a 26% chance that a movie with a "Long" runtime will have an "R" content rating.
- The likelihood of a movie having an "R" content rating is approximately 40.54%.
#### Popular Genres and Studios
- The most popular movie genres, by a significant margin, are Drama, Comedy, and Action & Adventure, with film counts of 3789, 3725, and 3551, respectively.
- Among production companies, Paramount Pictures, Warner Bros. Pictures, Universal Pictures, 20th Century Fox, and IFC Films have produced the most movies.
- The rise of "Netflix": Netflix experienced rapid growth in movie production starting in 2016. By 2018, it surpassed other major studios with an impressive output of 60 movies.



























