# Lyrics Analysis of favourite Spotify Artist
 Extract the lyrics from the songs of your favourite artist and analyse the commonly occuring words from Spotify.

Let’s break this down into smaller problems. We have to get the lyrics from our favourite artist. I have decided to go with Justin Bieber. 
Step 1: Connect to spotify
Step 2: Search all the albums for Justin Bieber
Step 3: Get the tracks from all Justin Bieber albums
Step 4: Get the lyrics of all the extracted tracks

Sounds easy, right? Now, how do we connect to Spotify? We use Spotipy.
## What is Spotipy?
Spotipy is a Spotify API for Python. It gives you access to all music data provided by the Spotify platform. 
First, we install spotipy.

pip install spotipy --upgrade

Connect to Spotify

In order to access all the data, you need a Spotify developer account. You can create one by simply signing in with your spotify account. Here’s the link to the page: https://developer.spotify.com/. You do not need a spotify premium for this. You have to register your app to get the credentials required for authorization.
In your developer account go to your dashboard and choose “create an app”. Fill in your app name and app description and  click create. Now you get access to a public key and private key.

