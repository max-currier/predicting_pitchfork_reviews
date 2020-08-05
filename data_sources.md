# Data sources

* [Music artists popularity](https://www.kaggle.com/pieca111/music-artists-popularity)
    * 1.4 Million names, tages, popularity from last.fm  
    * ARTISTS.CSV

* [18,393 Pitchfork Reviews](https://www.kaggle.com/nolanbconaway/pitchfork-data)
    * tables for artists, content, genres, labels, reviews, years
    * data from Chinese(?) music service, lots of asian pop song data
    * DATABASE.SQLITE
* [Spotify Playlist Curators](https://www.droptrack.com/spotify-playlist-curators/)  
    * scrapable
    * list of some curated playlist URLs but mostly smaller independent playlists  
* [Spotify Tracks DB](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db)
    * 232k spotify tracks, list made in 2019
* [Spotify Audio Features](https://www.kaggle.com/tomigelo/spotify-audio-features)
    * 130k trakc from spotify api, created in 2019
* [Million Song Dataset](http://millionsongdataset.com/)
    * audio features and metadata for a million contemporary popular music tracks
* [Datacamp genre prediction](https://www.datacamp.com/projects/449)
    * csv with lots of rock and hip hop Songs
    * fma-rock-vs-hiphop.csv
* [Spotify API](https://github.com/spotify/web-api-auth-examples)
    * DIFFICULT TO ACCESS
    * song attributes of spotify songs including playlist info
    * use [Spotipy module](https://spotipy.readthedocs.io/en/2.13.0/) to more easily access spoitfy data
* [KKBox's Music Recommendation Challenge](kaggle.com/c/kkbox-music-recommendation-challenge/data?select=songs.csv.7z)
    * UNABLE TO ACCESS


# Articles


* [A Machine Learning Deep Dive into My Spotify Data](https://opendatascience.com/a-machine-learning-deep-dive-into-my-spotify-data/)  
    * used spotify api to analyze liked songs
* [A List of Today's Top Independent Spotify Playlist Curators](https://blog.chartmetric.com/independent-spotify-playlist-curators/)
* [Analysis of Top Songs of 2017 on Spotify](https://www.kaggle.com/cihanoklap/top-songs-on-spotify-what-makes-them-popular)
    * highlights the common patterns behind the audio features of top songs
* [Music Genre Classification](http://cs229.stanford.edu/proj2018/report/21.pdf)
    * using KNN to determine genre


# Project ideas

* Predict most popular region for song based off spotify song attribute metadata  
* Predict likelihood or success or failure class of songs for playlist consideration on spotify  
* Predict critical reception based off pitchfork reviews, tie in spotify data (above/below 7, best new music
