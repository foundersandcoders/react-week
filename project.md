# Tamagotchi Project!

The goal is to build an interactive game-like thing that uses data from an API.

It should:

* Accept some user input (e.g. a username)
* Query an API (e.g. the [Github API](https://developer.github.com/v3/), or any other [fun one](https://www.potterapi.com/))
* Populate the UI with API data
* Have some form of persistent state and interactivity, e.g.
  * A hunger bar that decreases over time and is topped up when you feed them stars
  * A button to add more users to your collection
* Have integration tests using React Testing Library

### Stretch goals

* Save your state to localstorage so you can leave the page and come back later
* Have a button to add more copies of the game
* Make it look sick

### Examples

"interactive game-like thing" is a bit vague, so here are two example apps:

[Oli's Tamagotchi](https://tamagotchi.netlify.com)  
[Zooey's Drake thing](https://fuckin-yolo.netlify.com/)

### Setup

We're using [Create React App](https://create-react-app.dev/docs/getting-started) to handle all our bundling, linting etc.

1. `npx create-react-app my-app-name` generate the project (might take a while)
1. `cd my-app-name`
1. `npm start` start the dev server

Open the project in your editor—you should see an example app setup. Feel free to delete the logo/CSS/service worker that you won't be using.

### Deployment

We'll be deploying our apps to [Netlify](https://netlify.com).

1. Go to app.netlify.com and login with Github
1. Click the "New site from Git" button
1. Choose "Github" as your provider (and authorize it)
1. Choose the repo you want to deploy
1. Choose "Deploy site" (the build settings for CRA should be pre-filled)
