# indian_music_ml
a recommendation system for indian music
# indian_music_ml
a recommendation system for indian music
# Indian Music Recommendation System Report

## Introduction

This project implements a recommendation system for Indian music using the Spotify API and data analysis/visualization tools in Python. The system fetches artist and track data, processes playlists, and visualizes song popularity and other features.

## Data Collection

- **Spotify API**: The project uses the `spotipy` library to authenticate and interact with the Spotify API.
- **Artist Data**: Artist details (e.g., Shreya Ghoshal) are fetched, including genres, followers, and popularity.
- **Track Data**: Top tracks and albums for selected artists are retrieved.
- **Playlist Data**: Track IDs from a Spotify playlist are collected and detailed track features are extracted.

## Data Processing

- **Pandas**: Data is organized into DataFrames for further analysis.
- **Feature Extraction**: For each track, features such as name, album, artist, release date, length, and popularity are extracted.

## Analysis & Visualization

- **Popularity Filtering**: Songs with popularity above a threshold (e.g., >70) are filtered for focused analysis.
- **Scatter Plot**: A scatter plot visualizes the relationship between song length and popularity.
- **Pie Chart**: A pie chart shows the distribution of popularity among artists for highly popular songs.

## Example Visualizations

- **Scatter Plot**: Song Length vs. Popularity
- **Pie Chart**: Popularity of Songs Greater than 70 by Artist

## Usage

1. Install dependencies:
    ```sh
    pip install spotipy pandas plotly nbformat
    ```
2. Run the notebook cells to fetch data, process playlists, and generate visualizations.

## Files

- [`Untitled-checkpoint.ipynb`](.ipynb_checkpoints/Untitled-checkpoint.ipynb): Main notebook with code for data fetching, processing, and visualization.
- [`naija_playlist.csv`](.ipynb_checkpoints/naija_playlist.csv): Example output CSV with playlist data.

## Conclusion

This project demonstrates how to use the Spotify API and Python data tools to analyze and visualize Indian music data, providing insights into song popularity and artist trends.
