# liri-node-app

# LIRI-Bot

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

## LIRI uses the following commands:
1.	spotify-this-song
2.	concert-this
3.	movie-this
4.	do-what-it-says

## Technologies used:
•	Node.js  
•	Javascript  

## NPM packages:
•	spotify - A simple to use API library for the Spotify REST API.  
•	request - Request is designed to be the simplest way possible to make http calls. It supports HTTPS and follows redirects by default.  
•	dotenv - Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.  
•	moment – A lightweight JavaScript date library for parsing, validating, manipulating, and formatting dates.   

## How to Run LIRI-Bot.  

•	Step One: node liri spotify-this-song (song name here)  
This will show the following information about the song in your terminal/bash window:   
o	Artist(s)  
o	The song's name  
o	The album that the song is from  
If no song is provided then the program will default to "The Sign" by Ace of Base  

https://user-images.githubusercontent.com/22119689/62405784-b0d3db80-b556-11e9-9508-3d57eb410f5a.png
  
•	Step Two: node liri concert-this (artist here)    
This will show the following information about the concert in your terminal/bash window:    
o	Venue.  
o	Location.  
o	Date (MM/DD/YYYY).  

https://user-images.githubusercontent.com/22119689/62405786-b7fae980-b556-11e9-8d07-9be470e7d0a5.png

•	Step Three: node liri.js movie-this (movie name here)   
This will output the following information to your terminal/bash window  
o	Title of the movie.  
o	Year the movie came out.  
o	IMDB Rating of the movie.  
o	Rotten Tomatoes Rating.  
o	Country where the movie was produced.  
o	Language of the movie.  
o	Plot of the movie.  
o	Actors in the movie.  
o	Rotten Tomatoes URL.  
If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'  

https://user-images.githubusercontent.com/22119689/62405787-be896100-b556-11e9-94ee-3a8c80d3fe86.png
  
•	Step Four: node liri.js do-what-it-says  
This will output the command placed in random.txt file  
  
## Author
•	Nary Hang
