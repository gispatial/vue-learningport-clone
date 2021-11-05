# Vue Netflix Clone
A simple [Netflix](https://netflix.com) clone based on Vue powered by [Firebase](https://firebase.google.com). Please take note im not using Json feeds taken from https://itunes.apple.com/us/rss/topmovies/limit=100/json instead im using direct API's from MDB
<div>
</div>

## Live Demo
Link: https://

![example](https://github.com/Approxipix/vue-netflix-clone/blob/master/example1.png?raw=true)
![example](https://github.com/Approxipix/vue-netflix-clone/blob/master/example2.png?raw=true)
![example](https://github.com/Approxipix/vue-netflix-clone/blob/master/example3.png?raw=true)
![example](https://github.com/Approxipix/vue-netflix-clone/blob/master/example4.png?raw=true)


## Tech stack
* [Vue](https://github.com/vuejs/vue)
* [Vuex](https://github.com/vuejs/vuex)
* [Vue Router](https://github.com/vuejs/vue-router)
* [Firebase](https://firebase.google.com)
* [The Movie Database (TMDb)](https://www.themoviedb.org)

## Features
- [x] Authentication
  - [x] Sign up
  - [x] Sign in
  - [x] Sign in with Google
  - [x] Sign in with Facebook
  - [x] Sign in as demo user
  - [x] Recover password with email verification
  - [x] Logout
- [x] Movies
  - [x] Search movies
  - [x] List of movies by category
  - [x] List of movies with pagination
  - [x] Detailed information about the movie
  - [x] Fully responsive movie slider
  - [x] Add movie to "my list"
- [x] Responsive

## Configuration
To use this project with Firebase authentication, some configuration steps are required.
  1) Create a free Firebase account at [Firebase](https://firebase.google.com)
  2) Create a project from your [Firebase account console](https://console.firebase.google.com)
  3) Configure the authentication providers for your Firebase project from your [Firebase account console](https://console.firebase.google.com)
  4) Configuration required to connect to Firebase is defined in the `.env.local` file in the root of this repository
```js
VUE_APP_FIREBASE_API_KEY='AIzaSyBrHJBByHC7VEZvF_DmFrASkFLfOT2jB8Q'
VUE_APP_FIREBASE_AUTH_DOMAIN='rnfirebaseauth-8c0d3.firebaseapp.com'
VUE_APP_FIREBASE_PROJECT_ID='rnfirebaseauth-8c0d3'
VUE_APP_FIREBASE_STORAGE_BUCKET='rnfirebaseauth-8c0d3.appspot.com'
VUE_APP_FIREBASE_MESSAGING_SENDER_ID='122598877398'
VUE_APP_FIREBASE_APP_ID='1:122598877398:web:73519bb4ab8ee0b16c0177'
VUE_APP_TMDB_API_KEY='c04229b243150afc8110c3e5a45344ec'
```

## Installation
Clone project:
```shell
https://github.com/Approxipix/vue-netflix-clone.git
```

Then change into that folder:
```shell
cd vue-netflix-clone
```

Install project dependencies:
```shell
npm install
```

Build for production:
```shell
npm run build
```

Start up a local server:
```shell
npm run serve
```

Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

### Yours Sincerely
R. Aidy (Justed) - Senior Full Stack Dev/ Engineer
