# Angular 2 in 60 Minutes

This is the code for the 60 minutes tutorial. You can watch it <a href="https://www.youtube.com/watch?v=-zW1zHqsdyc">here</a>

## Prerequisites

Node.js and npm are essential to Angular development. 
    
<a href="https://docs.npmjs.com/getting-started/installing-node" target="_blank" title="Installing Node.js and updating npm">
Get it now</a> if it's not already installed on your machine.


## Install npm packages

```bash
npm install
npm start
```

## We also need
npm install typescript-compiler


## Issues
node_modules/protractor/built/browser.d.ts(258,37): error TS2503: Cannot find namespace 'webdriver'.
See
http://stackoverflow.com/questions/41238376/angular2-npm-install-didnt-find-namespace-webdriver
I.e. solution:
npm install @types/selenium-webdriver@2.53.36 --save-dev
