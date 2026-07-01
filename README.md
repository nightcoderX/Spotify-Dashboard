# Spotify Analytics Dashboard

An interactive Spotify dashboard built in **Power BI** using **Power Query Editor**, **DAX**, Charts and Slicers from a 2023 Kaggle dataset spanning **1000+ rows and 10+ attributes** across the dataset.
This project analyzes streaming patterns, top artists, popular tracks, and audio attributes such as **danceability, energy, valence, acoustics, and liveness**.


## Project Overview

This dashboard was created to explore Spotify 2023 data in a visual and structured way.  
It provides a clear view of:
- Total streams
- Top artists by streams
- Most popular tracks
- Streams by release year
- Tracks by key
- Relationships between audio features

## Dashboard Highlights

- **Total Streams** summary card
- **Audio feature gauges** for danceability, energy, and valence
- **Treemap** for streams by release year
- **Bar charts** for top artists and popular tracks
- **Scatter plots** for feature relationships
- **Track distribution by key**
- **Slicers** for filtering by:
  - Key
  - Released Year
  - Artist Name
  - Mode

## Tech Stack

- **Power BI**
- **Power Query Editor**
- **DAX Measures**
- **Data Cleaning and Transformation**
- **Data Visualization**
- **Dashboard Design and Storytelling**

## Dataset

- **Source:** Kaggle
- **Year:** 2023
- **Size:** 1K+ entries
- **Attributes:** 10+ columns


## Key Insights

- 383B+ total streams analyzed across the dataset.
- Taylor Swift is the most-streamed artist, followed by Ed Sheeran and Bad Bunny.
- "Shape of You" is the highest-streamed track (~3.6B streams).
= Danceability and Energy exhibit a moderate positive relationship.
= Most tracks have low liveness, suggesting studio-recorded music dominates the dataset.
= C♯ is the most common musical key, while D♯ appears least frequently.

## How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Load the dataset if needed.
3. Use the slicers to filter by artist, year, key, and mode.
4. Explore the charts to compare trends and patterns.

## Files in This Project

- `Spotify Dashboard.pbix` — Power BI report file
- `Demo Video.mp4`
- `spotify-2023.csv`

## Project Purpose

This project was created to practice:
- Data cleaning and transformation
- Building interactive dashboards
- Identifying patterns in music streaming data
- Presenting data in a professional business format

## Limitations

- The analysis is based on the available Kaggle dataset.
- Some insights may be limited by the number of records and the structure of the source data.
