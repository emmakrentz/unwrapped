# Spotify Unwrapped 2024

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
### 3. Install requirements
In terminal, run "pip install -r requirements.txt".
### 4. Run notebook
Open Unwrapped.ipynb and follow the instructions! All you need to do is copy in your access tokens and authorize your Spotify data and you're done! Happy unwrapping!

