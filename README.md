# spotamovie :movie_camera:

[![ Build Status](https://travis-ci.org/miguelgimenezgimenez/spotamovie-be.svg?branch=master)](https://travis-ci.org/miguelgimenezgimenez/spotamovie-be)

Connect to the Spotamovie API to get movie recommendations based on your Spotify playlists.
This is the backend for the spotamovie project
Github: https://github.com/johnandblue/spotamovieFE



## Spotamovie API

Full documentation available on Apiary: https://jsapi.apiary.io/previews/spotamovie/reference


## :iphone:Spotamovie iOS App

Check out our iOS App:

How long do you spend looking for a movie rather than actually watching a movie? Our app solves that problem for you! Spot A Movie is a mobile app, developed in React Native that allows users to connect with their Spotify accounts, and get movie recommendations based on their Spotify playlists.

![spotamovie app](./Landing.png)






## Tech Stack

**Server**: Node.js / Express

**Databases**: MongoDB, Redis

**Recommendation Engine**: [Raccoon](https://github.com/guymorita/recommendationRaccoon)

**Host**: Heroku

**Testing**: Mocha/Chai/Sinon

**Build Tool**: Travis CI



## APIs consumed

[Spotify](https://developer.spotify.com/web-api/)

[TMDB](https://www.themoviedb.org/documentation/api)



## Recommendation Example

|                     | User 1                   | User 2                   |
| ------------------- | ------------------------ | ------------------------ |
| 📻 **Songs Liked**  | \* "We are the Champions" | \* "We are the Champions" |
|                     | "Imagine"                | "We Built This City"     |
| 🎦 **Movies Liked** | *Star Wars*              | *E.T.*                   |
|                     | *Titanic*                | *Contact*                |
| **Possible Recs**   | *E.T*                    | *Star Wars*              |
|                     | *Contact*                | *Titanic*                |

\* = *Common Liked Song*


## Project Contributors
[Miguel Gimenez](https://github.com/miguelgimenezgimenez)

[Rod Reyes](https://github.com/2rod)

[JC Garcia](https://github.com/johnandblue)

[Varun Agarwal](https://github.com/vavarun)
