![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 07: NodeJS & NPM
===

## Submission Instructions
Follow the submission instructions from Lab 01.

## Resources
[Node JS Docs](https://nodejs.org/en/)

[NPM JS Docs](https://docs.npmjs.com/)

[Express JS Docs](http://expressjs.com/en/4x/api.html)

## Configuration
_Your repository must include:_

```
07-nodejs-npm-express
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── node_modules
├── package-lock.json
├── package.json
├── public
│   ├── data
│   │   └── hackerIpsum.json
│   ├── index.html
│   ├── new.html
│   ├── scripts
│   │   ├── article.js
│   │   └── articleView.js
│   ├── styles
│   │   ├── base.css
│   │   ├── fonts
│   │   │   ├── icomoon.eot
│   │   │   ├── icomoon.svg
│   │   │   ├── icomoon.ttf
│   │   │   └── icomoon.woff
│   │   ├── icons.css
│   │   ├── layout.css
│   │   └── modules.css
│   └── vendor
│       └── styles
│           ├── default.css
│           ├── normalize.css
│           └── railscasts.css
└── server.js
```

## Feature Tasks

*As a user, I want to be able to create new articles and allow guests to retrieve those new articles.*

- Initialize the project with `npm init`, which creates `package.json` and `package-lock.json` files. Don't forget to add `node_modules` to your `.gitignore` file!
-  Use NPM to install ExpressJS, and ensure that it's been saved as a dependency in the `package.json` file.


*As a developer, I want to use the ExpressJS framework to set up a server file to handle HTTP requests and deliver responses.*

- Instantiate the ExpressJS framework, configure the `app.use` middleware to interface with the file system, configure any needed routes, and tell the server to listen for incoming requests.
- Run the server using `node server` and ensure that your app functions correctly. If you'd like to have your code live re-load the way that `live-server` did, install the NPM package `nodemon` and use that to run your server.

### Stretch Goals
*As a user, I want to access the form directly so I can easily add new articles.*

- Create a route and callback that will serve up the new.html page via a separate URI.

*As a user, I want feedback if I have made an error so that I can make sure to always access the correct URL.*

- Create a ***404*** route to handle any requests other than index.html or new.html, and deliver a 404 status message to those invalid requests.

## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Joel Clair and Joe Waine
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview

We are initializing a node app while using the express framework to properly format routes and get comfortable with the MVC design pattern.


## Getting Started

Make sure you have the latest version of Node installed.
Install EXPRESS with npm install express
Install bodyparser with npm install body-parser


## Architecture

we created a copy of the starter code called joe-joel - We are using node, express, jquery and vanilla javascript.


