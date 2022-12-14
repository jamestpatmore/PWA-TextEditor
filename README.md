# PWA-TextEditor (Offline Compatibile//Using Webpack)

![javascript](https://img.shields.io/badge/Javascript-yellow)
![node.js](https://img.shields.io/badge/-node.js-green)
![manifest](https://img.shields.io/badge/-manifest-orange)
![webpack](https://img.shields.io/badge/MongoDB-blue)
![PWA](https://img.shields.io/badge/PWA-red)

## Description 

:writing_hand::writing_hand:
A text editor application that is both online and offline compatibile while also caching user input to enable top application performance for the user as well as feedback for the developer 

## Usage 

You may clone the repo and run the startup with 

```md 
npm run start
```

It already initiates the build as well with this command via a manual script within the package.json :brain:

Or with an easier GUI experenience you may go to the Heroku deployed application [here](https://pure-savannah-54385.herokuapp.com) :clinking_glasses:

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Outro 

Thank You for checking out my application!!!
if you'd like to contact me you can here..
[My Email](mailto:jamesthomaspatmore7@gmail.com)
[My Github](https://github.com/jamestpatmore)



