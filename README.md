# SpotifyGeneratePlaylist
A simple script that take your liked videos on Youtube, and generates a Spotify playlist based on the song in your liked videos.

## Table of Contents
* [Technologies](#technologies)
* [Setup](#setup)
* [Youtube](#video)
* [ToDo](#ToDo)

## Technologies
* [Youtube Data API v3]
* [Spotify Web API]
* [Requests Library v 2.22.0]

## LocalSetup
1) Install All Dependencies   
`pip3 install -r requirements.txt`

2) Collect You Spotify User ID and Oauth Token From Spotfiy and ddd it to secrets.py file
    * To Collect your User ID, Log into Spotify then go here: [Account Overview] and its your **Username**, just like its displayed in the image below
    ![alt text](images/userid.png)
    * To Collect your Oauth Token, Visit this url here: [Get Oauth] and click the **Get Token** button, just like its displayed in the image below
    ![alt text](images/spotify_token.png)

3) Enable Oauth For Youtube and add you client id into client_secrets.py file   
Ok this part is tricky but its worth it! Just follow the guide here [Set Up Youtube Oauth]

4) Run the File  
`python3 create_playlist.py`

## ToDo
* Unit Test File
* Add More Error Handling

   [Youtube Data API v3]: <https://developers.google.com/youtube/v3>
   [Spotify Web API]: <https://developer.spotify.com/documentation/web-api/>
   [Requests Library v 2.22.0]: <https://requests.readthedocs.io/en/master/>
   [Account Overview]: <https://www.spotify.com/us/account/overview/>
   [Get Oauth]: <https://developer.spotify.com/console/post-playlists/>
   [Set Up Youtube Oauth]: <https://developers.google.com/youtube/v3/getting-started/>