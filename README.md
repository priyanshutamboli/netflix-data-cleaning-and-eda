# Netflix Data Cleaning & Exploratory Data Analysis (Python)

## Overview
This project demonstrates a complete data cleaning and exploratory data analysis (EDA) workflow using Python on a real-world Netflix dataset. The objective is to transform raw data into an analysis-ready format and extract meaningful insights about Netflix’s content catalog.

## Dataset
- Netflix Titles Dataset
- ~8,700 movies and TV shows after cleaning
- Each row represents a unique title available on Netflix

## Project Workflow
1. Data cleaning and preprocessing
2. Feature engineering (dates and duration)
3. Exploratory data analysis using visualizations
4. Insight summarization

## Data Cleaning Highlights
- Preserved missing values in descriptive columns (director, cast, country)
- Removed invalid categorical entries
- Parsed and standardized date fields
- Split mixed-unit duration values into numeric value and unit
- Normalized multi-value categorical columns (genres, countries)

## Exploratory Data Analysis
The EDA explores:
- Distribution of Movies vs TV Shows
- Content growth over time
- Movie runtimes and TV show season counts
- Genre distribution
- Country-wise contribution to Netflix’s catalog

## Key Insights
- Movies dominate the Netflix catalog, though TV shows have increased steadily
- Content additions grew rapidly after 2015
- Most movies follow standard feature-length durations
- TV shows typically have a small number of seasons
- A small number of countries contribute a large share of content

## Tools Used
- Python
- pandas
- matplotlib
- seaborn

