# Unwrapped 2024

### Welcome to Unwrapped! 
Here you will find all sorts of data about your genres, your artists, your songs, and more! This notebook:
1. Intakes your Spotify data
2. Pulls lyrics from Genius for your top songs
3. Performs analysis
4. Generates personalized creatives

You will require Spotify and Genius API tokens which are free and easy to get. Here are the steps to run your own Unwrapped:
### 1. Set up your Spotify API credentials
Log into <a href = 'https://developer.spotify.com/dashboard'> the Spotify Dev site </a> and click "Create app" in the top right corner. App name and description can be whatever you want. Input "http://localhost/callback" as your Redirect URI. Check "Web API" and click Save. Now go to "Settings" in the top right corner, where you will find your Client ID and Client Secret. Copy these down.
### 2. Set up Genius API credentials
Log into <a href = 'https://genius.com/api-clients'> the Genius Dev site </a> and click "New API Client" on the left sideboard. App name can be whatever you want. You do need a real website for App Website URL. Click Save. Click "Generate Access Token" and copy this down.
### 3. Clone & Install requirements
In terminal, run "pip install -r requirements.txt".
### 4. Open Spotify
Find the playlist made by Spotify for Wrapped labelled "Your Top Songs 2024". Click on the 3 dots at the top, then "Add to other playlist" and create a new playlist. It doesn't matter what this playlist is called but it must be **your most recent playlist created** or this will not work.
### 5. Run notebook
Open Unwrapped.ipynb and follow the instructions. All you need to do is copy in your access tokens and authorize your Spotify data and you're done! I found this didn't work in Colab as the authorization never popped up, so local runs are likely better. Images will begin appearing in the "output_unwrapped" folder after a few minutes. Happy unwrapping!


Also Spotify API ToS prohibits using API data in ML models, I did not use any Spotify data in ML models :) Just NLP on the lyrics, for which all the data came from Genius and not Spotify. So please leave me alone if you are a Spotify lawyer.


