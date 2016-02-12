#frontend-starter

This is just a collection of npm scripts that make frontend prototyping fun and cool.

## motivation

It gets pretty tiresome assembling your grunt/gulp arsenal every time you want a simple workflow for developing some static html things.

This project includes some npm scripts that leverage bash and a handful of node modules to give a decent workflow out of the box.

## structure

```
dist/ - everything is built to here
images/ - images
scss/ - SASS things
src/ - JS things
pages/ - pages of your site/app as jade files
```

## scripts

### npm run dev

Watch sass, html, and js. Launches a browser via browser sync that reloads when changes happen to these things. Pretty much the only script you need.

### npm run watch-*

There are watch scripts that use the watch options of the tools involved. These are pretty much leveraged by the dev task.

### npm run build

`webpack` is used to build js and it is passed through a babel loader for ES6 things. `node-sass` is used to build sass.

### npm test

`jest` is included for js tests if that is your jam.
