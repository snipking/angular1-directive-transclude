# angular1-directive-transclude

[![Dependency Status](https://david-dm.org/snipking/angular1-directive-transclude/status.svg)](https://david-dm.org/snipking/angular1-directive-transclude#info=dependencies) [![devDependency Status](https://david-dm.org/snipking/angular1-directive-transclude/dev-status.svg)](https://david-dm.org/snipking/angular1-directive-transclude#info=devDependencies)

A branch based on [angular1-onsen-typescript-webpack](https://github.com/snipking/angular1-onsen-typescript-webpack.git)

Shows 2 use case for angular directive transclude

1. use ng-transclude with static directive template
2. use ngTranscludeFn in directive link function which load template dynamically and can be changed runtime

> Warning: Make sure you're using the latest version of Node.js and NPM

### Quick start

> Clone/Download the repo

```bash
# clone repo
$ git clone https://github.com/snipking/angular1-directive-transclude.git angular1-directive-transclude

# change directory to app root
$ cd angular1-directive-transclude

# install the dependencies with npm
$ npm install

# install the dependencies with bower
$ bower install

# run and watch changes
$ gulp run-dev
```

If everything goes right, chrome browser will open with url [http://localhost:8384/index.html](http://localhost:8384/index.html)
otherwise you should open it manually.

# Table of Contents

* [Getting Started](#getting-started)
    * [Dependencies](#dependencies)
    * [Installing](#installing)
    * [Running the app](#running-the-app)
    * [Developing](#developing)
    * [Testing](#testing)
* [License](#license)

# Getting Started

## Dependencies

What you need to run this app:
* `node` and `npm`

## Installing

* `npm install` to install build environment dependencies
* `bower install` to install javascript library dependencies
> choice angular >= 1.5.x if necessary

## Running the app

After you have installed all dependencies you can now run the app with:
```bash
gulp run-dev
```

It will start a local server using `webpack-dev-server`, and scripts build with webpack will watch, build (in-memory), and reload by it; other resources will watch by gulp. Chrome browser will open with url `http://localhost:8384/index.html`.

## Developing

### Build files

* developing build:  
```bash
gulp build-dev
```
* production build:  
```bash
gulp build-prod
```
* clean distribution (www) folder:  
```bash
gulp clean
```
* run and watch changes:  
```bash
gulp run-dev
```

### IDE

This project build with NetBeans 8.1, so the `nbproject` folder included. This is not required and if you are using other IDE, just delete it.

## Testing

#### 1. Unit Tests

_TODO_

# License

[APACHE](/LICENSE)
