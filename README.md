📊 Netflix 1990s Movie Data Analysis
A simple exploratory data analysis (EDA) project investigating Netflix movies released in the 1990s. The goal is to uncover trends and patterns—like the most common movie durations and the prevalence of short action films.

📁 Project Structure
text
Copy
Edit
├── netflixdata.csv         # The dataset used for analysis
├── netflix_eda.ipynb       # Main Jupyter notebook with full analysis
├── README.md               # Project documentation (this file)
🧠 Project Goals
Perform exploratory data analysis on Netflix's 1990s movie catalog.

Determine the most frequent movie duration in the 1990s.

Identify how many short action movies (less than 90 minutes) were released in that decade.

📌 Definitions
Short Movie: Any movie with a duration < 90 minutes.

1990s Decade: Movies released between 1990 and 1999, inclusive.

📊 Dataset Overview
The dataset (netflixdata.csv) includes the following columns:

Column Name	Description
show_id	Unique ID for each show
type	Either "Movie" or "TV Show"
title	Title of the movie or show
director	Director's name
cast	List of actors
country	Country of origin
date_added	Date added to Netflix
release_year	Year the title was released
duration	Duration (e.g., "90 min", "1 Season")
description	Short synopsis
genre	Genre/category of the movie/show

🛠 Tools Used
Python

Pandas for data manipulation

Matplotlib

🔍 Key Steps Performed
Data Cleaning: Filtered for only movies from the 1990s.

Duration Extraction: Converted duration from string to numeric (minutes).

Mode Calculation: Found the most frequent movie length.

Genre Filtering: Identified and counted short action movies.

Visualizations: plotted histograms.

📈 Results
Most Common Movie Duration: 93 minutes

Short Action Movies Released in the 1990s: 7 in total

✅ Future Improvements
Deep dive into genre trends over time.

Compare movie durations across decades.

Expand to TV shows or modern releases.