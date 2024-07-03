Music Player Web Application
Overview
This repository contains a simple and functional music player web application. The application fetches and displays songs from a server, allowing users to play, pause, and navigate through the songs. Each album is presented with its cover image and metadata.

Features
Fetch Songs: Retrieves songs from the server, displaying them in a playlist.
Play Music: Allows users to play, pause, and navigate between songs.
Album Display: Shows albums with cover images and metadata.
Time Display: Displays current playback time and duration of the song.
Volume Control: Adjusts the volume and allows muting/unmuting.
Responsive Design: Adapts to different screen sizes.
Directory Structure
Root Directory:

Contains the main HTML file, index.html.
Contains the main JavaScript file, script.js.
Contains the .htaccess file for server configuration.
Server Directory (/songs):

Contains subfolders for each album.
Each album subfolder contains info.json, cover.jpg, and MP3 files.
Key Files
index.html:
Main HTML structure of the application.
script.js:
Contains JavaScript functions to fetch and display songs and albums.
Manages playback controls, volume settings, and event listeners.
.htaccess:
Configures server to allow fetching of JSON, MP3, and image files.
Enables directory listing if needed.