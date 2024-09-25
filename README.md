# Power-BI-Dashboard
Project Purpose:
This project aims to analyze the Amazon Prime video content catalog to uncover patterns and insights regarding the types of shows and movies available on the platform. The analysis seeks to answer questions about content distribution based on categories such as genre, country of origin, and release year. Additionally, the dashboard can help users explore how the catalog evolves over time and understand content trends.

Dataset Overview:
The dataset contains information about 9,668 Amazon Prime video titles. The key columns in the dataset are:

show_id: Unique identifier for each title.
type: Indicates whether the title is a "Movie" or "TV Show."
title: The name of the title.
director: The director of the title (some entries may be missing).
cast: The main cast involved in the title.
country: The country of origin for the title (may be missing for many entries).
date_added: The date the title was added to the Amazon Prime catalog (very sparse).
release_year: The year the title was released.
rating: The content rating (e.g., PG-13, R, etc.).
duration: The duration of the title (in minutes for movies or seasons for TV shows).
listed_in: Genres/categories the title falls under.
description: A brief description or synopsis of the title.
Analysis Process:
Data Cleaning: Since there are missing values in columns like "director," "cast," "country," and "date_added," we either filled or excluded missing data during analysis where necessary. Additionally, transformations were done to standardize the "duration" and "rating" columns.
Data Categorization: We segmented the data by genres, ratings, release years, and countries to explore the variety in content.
Visualizations: Interactive visuals were created to display trends and distributions in content by release year, duration, country, and rating. The user can also filter by type (movie or TV show).
Insights from the Dashboard:
Content Release Trends: The majority of the content is released after the year 2000, with a peak in releases from 2010 onwards, indicating that Amazon Prime has focused on expanding its catalog in recent years.
Genre Distribution: The most common genres include "Drama," "Comedy," and "Action," showcasing a broad appeal in genres with more emphasis on these popular categories.
Country of Origin: A significant portion of content originates from the U.S., India, and the U.K., suggesting that Amazon Prime's catalog caters largely to English-speaking audiences, with some international appeal.
Content Ratings: Content for mature audiences (e.g., "R," "18+") is prominent, while there is also a notable portion of family-friendly content with ratings like "PG" and "13+."
Duration and Type: Movies tend to have durations of around 90 to 120 minutes, while TV shows are categorized by the number of seasons available.
By exploring these patterns, users of the dashboard can gain an understanding of how Amazon Prime's content library is structured and how it appeals to different demographics and audience preferences.
