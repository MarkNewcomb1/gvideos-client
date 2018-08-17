# gVideos

> gVideos

## Deployed URL
[gVideos](https://g90-videos.firebaseapp.com/)

## Deployed Backend URL
[Back End Live](https://gvideos-api.herokuapp.com/api/videos)

## Backend Repo
[Back End Repo](https://github.com/JoshAaronLevy/gvideos-server)

## Description

A web app specifically for web dev tutorial videos (YouTube videos already created), that filters the results based on a simple form of filter options (i.e. multi-check for languages, instructor, or select for video duration).

## Problem

Sites like YouTube rely solely on the search field to fetch and display results. But the results often include videos that include a different technology or language, or videos on a very different level (too remedial or too advanced) than what the individual is looking for.

## Solution

Our project - Galvanize Videos - will provide a simple, yet effective solution to this problem. Our project will allow users to narrow down the video results based on selected parameters in a simple Bootstrap form.

## UX

When a user visits the site, programming tutorial videos populate on the home page. But on the left hand side, there will be a simple Bootstrap form, allowing the user to select specific parameters and submit the form, which would reload the list of videos based on updated parameters.

## Technologies/Languages

1.  Vue (incl. Vue-Router and Vuex)
2.  Bootstrap-Vue
3.  Express+CORS+Body+Parser
4.  MongoDB
5.  Mongoose
6.  Shrike Videos API
7.  Heroku (back-end deployment)
8.  Firebase (front-end deployment)
9.  Mlabs (mongodb deployment)


## Collaborators

- Austin Loveless
- Levi Boenish
- Mark Newcomb
- Josh Levy

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
