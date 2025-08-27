# Data-Analysis-On-Netflix

# Netflix Data Analysis
Exploratory data analysis (EDA) on the Netflix dataset (netflix_titles.csv) to uncover insights about content types, release trends, directors, ratings, and durations using Python (Pandas, Matplotlib, Seaborn).

## Table of Contents
[Overview](#overview) - [Dataset](#dataset) - [Dependencies](#dependencies) - [Analysis Steps](#analysis-steps) - [Visualizations](#visualizations) - [Key Insights](#key-insights) - [How to Run](#how-to-run) - [Author](#author)

## Overview
Analyzes Netflix's content library to explore trends in Movies vs. TV Shows, release years, countries, directors, ratings, and durations through data cleaning, statistical analysis, and visualizations.

## Dataset
netflix_titles.csv includes: show_id (unique ID), type (Movie/TV Show), title, director, cast, country, date_added, release_year, rating (e.g., PG-13, TV-MA), duration (minutes/seasons), listed_in (genres), description.

## Dependencies
Python libraries: Pandas, Matplotlib, Seaborn, IPython. Install with: pip install pandas matplotlib seaborn

## Analysis Steps
1. **Load Data**: Read netflix_titles.csv into Pandas DataFrame.  
2. **Remove Duplicates**: Check and drop duplicate records.  
3. **Clean Data**: Fill missing director/cast with "Unknown"/"Not Available"; fill country/rating with mode; convert date_added to datetime, drop invalid dates; extract Year/Month.  
4. **EDA**: Analyze content types, top release years, Indian TV shows, top directors, ratings, durations, country production, monthly trends, and rating vs. duration.

## Visualizations
1. Cover Image: Stylized "NETFLIX DATA ANALYSIS" title (Matplotlib).  
2. Movies vs. TV Shows: Bar plot of content type distribution.  
3. Releases by Year: Bar plot of top 10 release years.  
4. Indian TV Shows: Bar plot of Indian TV shows by year.  
5. Top 10 Directors: Horizontal bar plot of directors by title count.  
6. Content by Rating: Bar plot of rating distribution.  
7. Movie Duration: Histogram of movie durations (minutes).  
8. TV Shows by Country: Horizontal bar plot of top 10 countries.  
9. Monthly Trends: Line plot of releases by month.  
10. Content by Country: Bar plot of top 10 countries by titles.  
11. Content Type by Rating: Heatmap of Movies/TV Shows by rating.  
12. Duration by Rating: Bar plot of average movie duration by rating.

## Key Insights
Movies outnumber TV Shows.  
Recent years show a surge in content releases.  
India has significant TV show production.  
Top directors contribute multiple titles.  
Common ratings: TV-MA, TV-14, PG-13.  
Movie durations vary, some ratings (R, TV-MA) have longer averages.  
US leads content production, followed by India, UK.  
December/January see higher releases, likely due to holidays.

## How to Run
1. Clone repo: git clone <repository-url>  
2. Place netflix_titles.csv in project directory.  
3. Install dependencies: pip install pandas matplotlib seaborn  
4. Run in Jupyter: jupyter notebook netflix_data_analysis.ipynb  
5. Execute notebook cells for analysis and visualizations.
