# Netflix Dataset Analysis

## Objective:
Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries.

boliviainteligente-OsCODx_vi6U-unsplash.png

## Dataset Information:
Netflix is one of the most popular media and video streaming platforms.They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally.
This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.
### Source:
Please check the description at: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/000/940/original/netflix.csv

## Feature Information:
Show_id: Unique ID for every Movie / Tv Show
Type: Identifier - A Movie or TV Show
Title: Title of the Movie / Tv Show
Director: Director of the Movie
Cast: Actors involved in the movie/show
Country: Country where the movie/show was produced
Date_added: Date it was added on Netflix
Release_year: Actual Release year of the movie/show
Rating: TV Rating of the movie/show
Duration: Total Duration - in minutes or number of seasons
Listed_in: Genre
Description: The summary description

## Key Highlights:

### Defining Problem Statement and Analyzing Basic Metrics:
1. Analyzed basic metrics to provide a foundation for subsequent analysis.
### Data Overview and Pre-processing:
1. Examined data shape and types.
2. Converted categorical attributes to 'category' where necessary.
3. Detected missing values and provided a statistical summary.
4. Unnesting the columns.
### Non-Graphical Analysis:
1. Conducted value counts for each attribute.
2. Identified unique attributes.
### Visual Analysis after Pre-processing:
1. Univariate Analysis for Continuous Variables: Utilized Distplot, countplot, and histogram.
Provided insights into the distribution of continuous variables.
2. Bivariate Analysis for Categorical Variables: Used Boxplot for categorical variables.
Explored relationships and variations among categories.
3. Correlation Analysis: Used Heatmaps and Pairplots to visualize correlations.
Discussed insights derived from the correlation analysis.
### Missing Value & Outlier Check:
1. Identified missing values.
2. Optional treatment for outliers.
### Exploratory Questions for Analysis:
1. How has the number of movies released per year changed over the last 20-30 years?
2. Comparison of tv shows vs. movies.
3. What is the best time to launch a TV show?
4. Analysis of actors/directors of different types of shows/movies.
5. Does Netflix has more focus on TV Shows than movies in recent years?
6. Understanding what content is available in different countries.
