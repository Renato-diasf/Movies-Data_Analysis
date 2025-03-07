# Movie Data Analysis: Exploring Ratings and Metadata

## Overview
This project focuses on analyzing movie data from two primary sources: the MovieLens dataset (ratings) and the TMDB 5000 dataset (metadata). The goal is to explore patterns in movie ratings, understand the distribution of ratings, and analyze metadata such as genres, languages, and budgets. The analysis includes data cleaning, statistical summaries, visualizations, and comparisons between different movies and categories.

## Datasets
1. **MovieLens Dataset**:
   - Contains user ratings for movies.
   - Columns: `userId`, `movieId`, `rating`, `timestamp`.
   - Ratings range from 0.5 to 5.0.

2. **TMDB 5000 Dataset**:
   - Contains metadata for 5000 movies.
   - Columns: `budget`, `genres`, `original_language`, `popularity`, `revenue`, `runtime`, `vote_average`, `vote_count`, etc.

## Project Structure
The analysis is divided into the following sections:

1. **Data Exploration**:
   - Understanding the structure of the datasets.
   - Exploring basic statistics (mean, median, standard deviation) for ratings and metadata.

2. **Rating Analysis**:
   - Distribution of ratings across all movies.
   - Comparison of ratings for specific movies (e.g., Toy Story vs. Jumanji).
   - Calculation of average ratings per movie and their distributions.

3. **Metadata Analysis**:
   - Distribution of movies by original language.
   - Analysis of budgets, revenues, and runtimes.
   - Exploration of genres and their popularity.

4. **Visualizations**:
   - Histograms and box plots for ratings and metadata.
   - Bar plots and pie charts for categorical data (e.g., languages, genres).

## Tools and Libraries
- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Seaborn**: Data visualization.
- **Matplotlib**: Additional plotting capabilities.

## Key Insights
- The average rating across all movies is approximately **3.57**, with a median of **4.0**.
- Movies like *Toy Story* have higher average ratings (**3.90**) compared to movies like *Jumanji* (**3.37**).
- The majority of movies in the TMDB dataset are in **English**, with a significant drop in frequency for other languages.
- Budget and revenue distributions show that most movies have modest budgets, with a few blockbusters skewing the data.
