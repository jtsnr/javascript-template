# javascript-template
A template for JavaScript projects.

Taken from Pluralsight course "Building a JavaScript Development Environment"

https://github.com/coryhouse/javascript-development-environment

## Package Managers
* npm

## Security
```bash
npm audit
```
* Alternatives: [snyk](https://snyk.io/)

## Development Web Server
* express
* Alternatives: node http-server, webpack dev server, browsersync

## Sharing Work-in-progress
* [localtunnel](https://github.com/localtunnel/localtunnel)
* Alternatives: ngrok, vercel, surge

## Automation
* npm scripts
* Alternatives: grunt, gulp
* npm-run-all - to run multiple things at the same time

## Transpilers
* babel
* Alternative: TypeScript

## Bundling
* webpack
* Alternatives: browerify, rollup, parcel, snowpack

## Linting
* eslint, eslint-watch

## Unit Testing
* mocha, chai
* Frameworks: mocha, jasmine, tape, ava, jest
* Assertion libraries: chai, should.js, expect
* Helper libraries: jsdom, cheerio

## Continuous Integration
* Travis
* GitHub Action (node.js.yml)
* Alternatives: appveyor, jenkins, circleci, semaphore, snapci

## HTTP Calls
* Node: http, request
* Browser: XMLHttpRequest, jQuery, Framework-based, Fetch
* Node & browser: isomorphic-fetch, xhr, SuperAgent, Axios

## Mock HTTP
* Declare schema: JSON Schema Faker
* Generate random data: faker.js, chance.js, randexp.js
* Serve Data via API: JSON server
* Alternatives: Nock, static JSON, api-mock

## Production Deploy
* Recommendation to keep UI and API separate
* Can utilise cheap UI hosting; CDN
* Can use different tech for API

## Cloud Hosting
* AWS, Azure, Heroku, Firebase, GCP,
* Static front ends: Netlify, GitHub Pages, Surge