# 🎵 AI-Powered Productivity Playlist Classifier

## Overview
This project aims to predict whether a playlist boosts productivity or not using machine learning. By analyzing musical features (like tempo, energy, danceability) and metadata from playlists, the model can classify playlists as **productive** or **non-productive**.

As a music enthusiast, I often rely on music to focus, but sometimes it distracts me. This project was born from the curiosity to quantify which playlists actually help productivity.

## Features
- **Playlist Analysis**: Extracts relevant audio features from playlists or individual songs.  
- **Data Preprocessing**: Handles missing data, scales, and transforms features to fix skewness.  
- **Machine Learning Models**: Trains classifiers to distinguish productive vs. non-productive playlists.  
- **Performance Visualization**: Graphical comparison before and after data preprocessing.  
- **Cross-Validation & Accuracy Metrics**: Evaluates model robustness and reliability.  

## Dataset
The dataset includes musical features such as:  
- Energy  
- Danceability  
- Tempo  
- Valence  
- Instrumentalness  
etc.

**Note:** Labels for productivity were generated based on clustering techniques using key features that affect focus and energy.
