# spotify-music-recom

## Overview
This project implements a Music Recommender System using Streamlit and Spotipy, integrated with the Spotify API. It allows users to select a song and receive recommendations based on similarity metrics.

## Features
- Select a song from a dropdown menu.
- Display top 5 recommended songs based on similarity.
- Show album covers of recommended songs using Spotify API.

## Technologies Used
- Python
- Streamlit
- Spotipy
- Pandas
- Pickle

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Xerp839/spotify-movie-recom.git
   cd spotofy-movie-recommender
   
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

<!-- -->

3. Run the Streamlit application
   ```bash
   streamlit run app.py

<!-- -->

## File Structure
-app.py: Main application file containing Streamlit app logic.
-home.py: Contains functions for displaying the home page.
-contact.py: Placeholder for contact page functionality.
-df.pkl: Pickled file containing music data.
-similarity.pkl: Pickled file containing similarity metrics.
-Model Training.ipynb: To train model and create pkl file (recommended to delete the pkl files and use the one after running this file)

## Usage
Select a song from the dropdown menu.
Click "Show Recommendation" to display recommended songs and album covers.

   
   




