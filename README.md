# 2009scape Website

![](./particle.jpg)

A non-interactive website where you can host download links, community links, and whatever else you want too.

For an interactive, more beefy website, check out [2009scape-Web](https://github.com/2009scape/2009Scape-Web)

Features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Running the site locally

In order to compile the assets and run Jekyll on local you need to follow those steps:

(Note: This guide assumes you know where to find programs/add things to your path. Join our [Discord](https://discord.gg/43YPGND) if you need help.)

- Install [NodeJS](https://nodejs.org/)
- Install [Jekyll](https://jekyllrb.com): `sudo gem install bundler jekyll`
- Install [Yarn](https://yarnpkg.com/): `npm install -g yarn`
- Install dependencies: `yarn`
  - Note: One of the dependencies requires `python2`
- Run: `gulp`

**Don't forget to change your url before you deploy your site!**

## Color and Particle Customization
- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Credits

This project was taken from [Nathan Randecker](https://github.com/nrandecker/particle). Big thanks to him and his generous license.
