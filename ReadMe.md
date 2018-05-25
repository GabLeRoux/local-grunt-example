# Sample grunt project

[![Build Status](https://travis-ci.com/GabLeRoux/local-grunt-example.svg?branch=master)](https://travis-ci.com/GabLeRoux/local-grunt-example)

```bash
git init
npm init
npm i --save-dev grunt bower
npm i --save-dev grunt-contrib-uglify grunt-sass load-grunt-tasks
npm run bower -- init
npm run bower -- i font-awesome bootstrap jquery requirejs angular
```

Relevant files:

* [bower.json](/bower.json)
* [package.json](/package.json)
* [Gruntfile.js](/Gruntfile.js)

## Setup ci

```bash
travis init
```