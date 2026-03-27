# Interactive Spotify API Dashboard

Status: Work in progress — Expected completion: Summer 2026

An interactive Python + Streamlit dashboard to explore Spotify music data (artist stats, track audio features, album info, and quick insights). Primary implementation uses Streamlit for the UI and the Spotify Web API (via Spotipy) for live data.

## Technologies Used
- Python 3.8+
- Streamlit (interactive web app)
- Spotipy (Spotify Web API client / OAuth)
- Pandas (data manipulation)
- Matplotlib / Seaborn / Plotly (visualizations)
- DuckDB / Parquet 

## Features
- Live Spotify API integration: search artists, fetch top tracks, audio features, and album info
- Interactive filters: artist, album, release year, popularity range
- Visualizations: distributions (popularity, danceability, energy, valence), correlation heatmaps, top-artist charts
- Download filtered CSV of queried results
- Support for reading local CSV/Parquet as a fallback or for reproducible demos

## Data Source
The data used in this dashboard is sourced from the Spotify API, providing real-time access to a vast music database.

### Repository status & planned work

# Current: 
-README and plan in place. Core Streamlit app (app.py) and Spotipy integration to be added.

# Planned:
-app.py with Spotipy OAuth flow + CSV fallback
-example .env template and instructions for Spotify credentials
-requirements.txt (pinned)
-sample dataset (small) for local demo
-screenshots and short demo GIF
-deployment guide (Streamlit Community Cloud and AWS container option)
