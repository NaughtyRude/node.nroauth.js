# nr-oauth

OAuth2 **server-side** authorization module for
[Node.js](http://www.nodejs.org).

## Installation

```bash
$ npm install nr-oauth
```

## API

### NROAuth#urlToConnect(resource)

Return the url that points to first step for get the access token.

### NROAuth#code(code)

Set the code to request the access token.

### NROAuth#requestAccessToken(fn)

Start the OAuth2 request to NaughtyRude.com and execute the callback function when it's done.

## Simple example application

See the [example documentation](./example/Readme.md) to run the app