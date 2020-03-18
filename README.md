# The Vishual Project

This is the back end to the Vishual Project, a music visualiser that runs in the browser using the Spotify API.

## Spotify Accounts Authentication

This project contains the code for [authenticating against the Spotify Web API](https://developer.spotify.com/web-api/authorization-guide/).

## Installation

These examples run on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it. You can also follow [this gist](https://gist.github.com/isaacs/579814) for a quick and easy way to install Node.js and npm.

Once installed, clone the repository and install its dependencies running:

    $ npm install

## Running the examples

In order to run the Authorization Code flow do:

```
    $ cd authorization_code
    $ node app.js
```

Then, open `http://localhost:8888` in a browser.
