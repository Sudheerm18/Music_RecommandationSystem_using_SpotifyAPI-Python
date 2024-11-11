# Music_RecommandationSystem_using_SpotifyAPI-Python

# 🎶 Music Recommendation System using Spotify API and Python 🎶

Welcome to the **Music Recommendation System** project! This repository demonstrates how to build a recommendation system that provides personalized music suggestions based on users' listening behavior, preferences, and song features, using **Spotify API**, **Python**, and **Data Science** techniques.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## 🎼 Introduction
This project is a practical application of **Data Science** and **Machine Learning** in the music industry. The Music Recommendation System suggests songs by analyzing an individual's music tastes and finding similar tracks. It combines **content-based filtering** and **popularity-weighted scoring** to generate balanced recommendations that are both relevant and trendy.

By accessing **Spotify's vast music catalog** through their API, the project showcases how to utilize real-time data in action and learn the fundamentals of building a recommendation engine from scratch.

## ✨ Features
- **Content-Based Filtering**: Recommends songs based on similarities in audio features like tempo, energy, and danceability.
- **Popularity-Weighted Scoring**: Adjusts recommendations based on the popularity of tracks, with a higher emphasis on recent releases.
- **Hybrid Recommendation System**: Combines content-based recommendations with weighted popularity for a more personalized experience.
- **Spotify API Integration**: Uses the Spotify API to fetch track metadata, audio features, and popularity scores.

## 🛠️ Technologies Used
- **Python**: Main programming language for the project.
- **Spotify API**: Used to fetch real-time music data and metadata.
- **Pandas**: For data manipulation and analysis.
- **Scikit-Learn**: For cosine similarity calculations in content-based filtering.
- **Jupyter Notebook**: For interactive development and visualization.

## 🚀 Setup and Installation

### Prerequisites
- Python 3.6+
- A **Spotify Developer Account**. Sign up [here](https://developer.spotify.com/dashboard/).
- A **Client ID** and **Client Secret** from your Spotify Developer Dashboard.

### Installation
1. **Clone this repository**:
   ```bash
   git clone https://github.com/sudheerm18/music-recommendation-system.git
   cd music-recommendation-system
