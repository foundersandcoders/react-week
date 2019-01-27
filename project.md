# Tamagotchi Project!

The goal is to build an interactive game-like thing that uses data from an API.

It should:

* Accept some user input (e.g. a username)
* Query an API (e.g. the [Github API](https://developer.github.com/v3/), or any other [fun one](https://www.potterapi.com/))
* Populate a UI with API data
* Have some form of persistent state and interactivity, e.g.
  * A hunger bar that decreases over time and is topped up when you feed them stars
  * A button to add more users to your collection
* Have integration tests! (and units tests if they're relevant)

Try to:

* Write modular code: one component per file
* Separate your container logic from presentational components

### Stretch goals

* Save your state to localstorage so you can leave the page and come back later
* Have a button to add more copies of the game
* Make it look sick

### Examples

"interactive game-like thing" is a bit vague, so here are two example apps:

[Oli's Tamagotchi](https://tamagotchi.netlify.com)  
[Zooey's Drake thing](https://fuckin-yolo.netlify.com/)

### Setup

We'll go through the project setup together. All the information is in [this repo](https://github.com/oliverjam/minimal-react-setup)

### Deployment

You can deploy your app to [Netlify](https://netlify.com) (or any other static host). There are [more instructions](https://github.com/oliverjam/minimal-react-setup/blob/master/docs/deploying.md) in the setup repo.
