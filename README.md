# Spotify React App
Following Joe Karlsson's [tutorial](https://levelup.gitconnected.com/how-to-build-a-spotify-player-with-react-in-15-minutes-7e01991bc4b6), I learned how to create a React app that connects to the [Spotify API](https://developer.spotify.com/dashboard/applications) so that it displays information about the current song you're listening to. 

In his tutorial, Joe created an app that displayed the album cover, song title, artist, and whether the song was currently playing or paused. In my recreation of this app, I added the album title and the rate of the album's popularity from (0-100). If the popularity ranks 50 or above, the UI will display the current song's information along with the word "Mainstream" to describe the user's taste in music based on that one song. If the popularity ranks below 50, the description will read, "Wow! You're hip."

This React app was set up by following the instructions on the [Create React App](https://github.com/facebook/create-react-app) project generator developed by Facebook.

![Spotify React App](spotify-react-app.png)
