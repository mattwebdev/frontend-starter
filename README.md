#frontend-starter

This is just a collection of npm scripts that make frontend prototyping fun and cool.

## motivation

It gets pretty tiresome assembling your grunt/gulp arsenal every time you want a simple workflow for developing some static html things.

This project includes some npm scripts that leverage bash and a handful of node modules to give a decent workflow out of the box.

## structure

```
dist/ - everything is built to here
images/ - images
scripts/ - supporting build scripts
scss/ - SASS things
src/ - JS things
index.html - a single html page
```

## scripts

### npm run dev

Watch sass, html, and js. Launches a browser via browser sync that reloads when changes happen to these things. Pretty much the only script you need.

### npm run watch-*

There are watch scripts that use the `watch` node module to watch various types of assets. One for sass, one for js, one for html.

### npm run build

`webpack` is used to build js and it is passed through a babel loader for ES6 things. `node-sass` is used to build sass.

### npm test

`jest` is included for js tests if that is your jam.
