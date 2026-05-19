# synent-task-task3-Exploratory-Data-Analysis-EDA--Kanksha
# Netflix Data Analysis using Python

## Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix dataset using Python. The analysis helps identify trends, patterns, and insights related to Netflix content such as movies and TV shows.

## Objective
- Analyze Netflix content trends
- Identify patterns in genres, ratings, and release years
- Perform correlation analysis and visualization
- Generate insights using data analysis techniques

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Columns
- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

## Steps Performed

### 1. Data Loading
- Imported dataset using Pandas
- Verified dataset structure using:
  - head()
  - info()
  - describe()

### 2. Data Cleaning
- Checked missing values
- Removed duplicates
- Converted duration column into numeric format
- Converted date_added into datetime format

### 3. Exploratory Data Analysis
Performed analysis on:
- Content type distribution
- Release year trends
- Movie duration analysis
- Top genres
- Country-wise content
- Ratings distribution

### 4. Correlation Analysis
Generated heatmap to analyze relationships between:
- release_year
- duration

### 5. Data Visualization
Created:
- Count plots
- Bar graphs
- Histograms
- Heatmaps
- Trend analysis charts

## Key Insights
- Movies were more frequent than TV shows.
- Drama and International Movies were among the most common genres.
- Netflix content increased significantly after 2015.
- Correlation between release year and duration was weakly negative.

## Conclusion
This project helped in understanding:
- data preprocessing,
- exploratory data analysis,
- statistical summaries,
- trend analysis,
- and visualization techniques using Python.

It also provided practical experience with real-world datasets and business-oriented insights generation.
