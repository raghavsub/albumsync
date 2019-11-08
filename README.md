# albumsync
A Python script for putting all of your Spotify albums into one playlist

## Installation

To install albumsync, clone the repo and install the dependencies:

``` bash
git clone https://github.com/raghavsub/albumsync.git
cd albumsync
pip install -r requirements.txt
```

Next, set up an application in your Spotify developer [dashboard](https://developer.spotify.com/dashboard/applications) and set the `SPOTIFY_CLIENT_ID`, `SPOTIFY_CLIENT_SECRET`, and `SPOTIFY_REDIRECT_URI` environment variables as described [here](https://spotipy.readthedocs.io/en/latest/#authorization-code-flow).

## Quickstart

Albumsync populates an existing playlist ("All Albums" by default) with the contents of your saved albums:

``` bash
./albumsync <your Spotify username>
```
