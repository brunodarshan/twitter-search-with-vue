# TwitterSearchWithVue
__Search Twitter API With VueJS__

A simple component builded with VueJs and Twitter API with a ExpressJS Middleware

## How I Use

Firstly register a app on Twitter. Then setup the configurations on `index.js`.

``` 
config = {
  consumer_key: '..',
  consumer_secret: '..',
  access_token: '..',
  access_token_secret: '..'
}
``` 

### 1 - How I Use (Production Mode)

- Clone this repository
- Run ``yarn``
- Run ``yarn build`` to build the source
- Run ``yarn net``

### 2 - How I Use (Development Mode)

- Run ``yarn``
- Run ``yarn devel``

**NOTE**: If you use in __Development Mode__, the extension [Allow-Cross-Allow-Origin:*](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi) in Google Chrome will help you to running this project without problems with CORS.

**NOTE 2**: If you clone and use this project in a work, remember of change the tokens and secrets.
