## About

This is the angular front end that authenticates with auth0 and calls a protected api served by
and protected by Spring Boot. Specifically this client front end runs at http://localhost:3000 and makes
a call to http://localhost:8080/secured/ping after it has received a token from auth0.

## Setup
auth0-variables.js needs to use setup variables from you auth0 app.

## Running

In project root directory run `python -m SimpleHTTPServer 3000`
Go to [http://localhost:3000](http://localhost:3000) and you'll see the app running
