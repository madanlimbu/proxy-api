# Proxy API

Proxy API service, helpful for quick dummy api data or overcoming CORS in other project during development.

## Getting Started

Once you have the clone of the repo. Install the dependencies, current development url is [http://localhost:9000](http://localhost:9000).

We are using nodemon during development.

Project Summary : 

    src 
        - js (contains frontend react components)
        - scss (global scss)
    utils  (backend experss server utils)
    index.js (express stuff)
         
### Prerequisites

- node

### Installing

Instal modules and run express server with nodemon
```
cd proxy-api
npm install
npm run server
```

Run webpack watch on new Terminal for frontend compilation

``
npm run watch
``

## Running the tests

Get the local server started then find a CORS blocking endpoint. On the browser got to [http://localhost:900/get?q=some_cors_blocked_endpoint]().

We should be able to get the data in browser. Then on your project in JS call this endpoint to get the data.
 
## Built with

- node
- express
- request

## Versioning

We use [SemVer](https://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/madan95/dockerTemple/tags).

## Author

- Madan Limbu
