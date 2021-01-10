# Armin's Notes
## Summary 
This repository contains all of the notes taken by [Armin](https://github.com/parniaa) for the Lighthouse Labs Web Development Bootcamp.

## Table of contents
* [Week 1](/Week_1)
  * [Weekend](/Week_1/WEEKEND)

#### Library Module Package

Library: an independent collection of code that can be used by programs (not JS specific) - Module: JS code in a separate file, that can be required by other JS programs - Package: a collection of JS modules, with a package.json, usually published on NPM


### Running the test
#### Setting up the project
1. Create a new project directory and then
```
npm init -y
```
2. Create a seperate directory for test call it test and add nameTest.js


3. npm install these packages in test directory:
```
npm install mocha chai --save-dev.
```

4. Update the package.json test script
```
("scripts": {
  "test": "./node_modules/mocha/bin/mocha"
}
```
5. then run the test
```
npm test
```
