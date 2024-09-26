# Spotify Web Player Clone

This project is a simple clone of the Spotify web player. It is built using HTML, CSS, and JavaScript. The player includes features like viewing playlists, playing/pausing songs, volume control, and more.

## Features

- Display and interact with a playlist of songs.
- Play, pause, and skip songs.
- Seek through the song using the progress bar.
- Volume control, with options to mute/unmute.
- Navigation bar for toggling between home and search views.
- Display albums with details fetched from the server.

## Project Structure

```plaintext
├── assets              # Icons and images
├── css                 # Stylesheets (style.css and utility.css)
├── js                  # JavaScript files (script.js)
├── songs               # Songs
├── index.html          # Main HTML file
└── README.md           # Project documentation
```
## Getting Started

- Clone the repository:
<code> git clone https://github.com/your-username/spotify-clone.git</code>
- Open ```index.html``` in your browser.
- Make sure you have a server setup to host the audio files, as the app fetches songs dynamically from the server. [ Even potato pc may work ]

## Usage
- To load and play songs, add your ```.mp3``` files to the appropriate directory and ensure your server returns the song list correctly.
- Album information should be available in ```info.json``` files within the respective folders.
- Controls such as ```play/pause```, ```previous/next```, and ```volume``` control work directly in the player interface.

## Disclaimer
<code>This is simply my personal project and is not affliated with spotify</code>