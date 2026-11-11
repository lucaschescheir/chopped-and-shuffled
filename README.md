# Chopped & Shuffled

A single-page road trip DJ for Spotify. Everyone in the car adds their genres and/or playlists, and the mix takes turns between passengers so everyone gets their songs.

## Setup
1. Create an app at https://developer.spotify.com/dashboard (Web API + Web Playback SDK).
2. Add the Redirect URI shown on the page (e.g. `https://<you>.github.io/chopped-and-shuffled/` or `http://127.0.0.1:8888/` locally).
3. Add the Spotify accounts that will log in under **User Management**.
4. Open the page, paste the Client ID, and connect. Playback control needs Spotify Premium.

Run locally: `python -m http.server 8888 --bind 127.0.0.1`
