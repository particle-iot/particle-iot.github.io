# Particle Source

> The website for organizing all of Particle's open source repositories.

### Generating static content

This repository generates static content using [Assemble](http://assemble.io), a Jekyll-like static site generator for Node.js.

First, clone this repository. You'll need Node and npm.

Install grunt:

`npm install -g grunt-cli`

Then install dependencies:

`npm install`

Now, to build the static content:

`grunt build`

To run a local server and watch for new content, complete with livereload:

`grunt server`

To deploy your new content:

`grunt publish`

### License

MIT.