# SpotifyConnector
Code to access and operate on our Spotify playlists for Backups and potentially further analysis.

## Relevant Links

- [Spotify API](https://developer.spotify.com/documentation/web-api/)
- [Python Wrapper for Spotify API - Spotipy](https://github.com/plamere/spotipy)
- [Python Wrapper for Spotify API - Tekore](https://pypi.org/project/tekore/)

There are more wrappers available for other languages; checkout the [documentation on API wrappers](https://developer.spotify.com/documentation/web-api/libraries/).

## Initial Research

A user's saved tracks seem to be their 'liked songs'. However, they might actually not be.
Todo: Ensure that 'saved tracks' == 'liked songs'.

- [API reference /get-users-saved-tracks](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-users-saved-tracks)
- [API reference /get-current-user-saved-tracks](https://developer.spotify.com/console/get-current-user-saved-tracks/)
- [Retrieve over 50 songs despite the cap](https://github.com/spotify/web-api/issues/1321)
