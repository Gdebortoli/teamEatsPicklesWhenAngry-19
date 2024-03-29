# Tech Blog App

## Description

A text editor application that runs in a web browser. This will be a one page application that can also function offline 

### User Story

* AS A developer I WANT to create notes or code snippets with or without an internet connection SO THAT I can reliably retrieve them for later use

## Table of Contents

- [Objectives](#objectives)
- [Assets](#assets)
- [Installation](#installation)
- [Deplyment](#deployment)
- [Github Link](#github-link)

## Objectives

GIVEN a text editor web application

* WHEN I open my application in my editor
THEN I should see a client-server folder structure
* WHEN I run `npm start` from the root directory
THEN I find that my application should start up the back end and serve the client
* WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB database
* WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
* WHEN I load my web application
THEN I should have a registered service worker using Workbox
* WHEN I register a service worker
THEN I should have my static assets precached upon loading along with subsequent pages and static assets
* WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application

## Assets

* idb
* Heroku
* JavaScript
* Webpack
* Workbox
* Babel

## Screenshot

![SC of homepage](./client/src/images/Screen%20Shot%202023-01-21%20at%202.08.54%20AM.png)

## Installation

* Clone the repository
* run $ npm install in command line
* run $ nodemon server to start the server 

## Deployment 

[Heroku](https://teameatspickleswhenangry-19.herokuapp.com/)


## Github Link

Click here for the link to my [Github Respository](https://github.com/Gdebortoli/Text-Editor.PWA.19) 
