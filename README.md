# DevOps Challenge Web App

## Requirements

You'll need Node.js 5.x version.
Install NPM dependencies: `$ npm install`

## Build project

Run gulp with next ENV variables: `$ ENDPOINT=localhost ENDPOINT_PORT=8000 ./node_modules/.bin/gulp`
ENV variables specifies API endpoint to connect with.

## Run projects

Build contains only one static index.html, so you can serve it through Nginx.
If you want to run it for test locally: `$ cd dist && python -m SimpleHTTPServer 9000`
