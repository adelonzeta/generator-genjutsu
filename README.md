# Genjutsu

[![npm](https://img.shields.io/npm/v/generator-genjutsu.svg?colorB=4CC61E)](https://www.npmjs.com/package/generator-genjutsu)
[![license](https://img.shields.io/github/license/adelonzeta/genjutsu.svg?colorB=4CC61E)](https://github.com/adelonzeta/genjutsu/blob/master/LICENSE)
[![dependencies](https://img.shields.io/librariesio/github/adelonzeta/genjutsu.svg)](https://www.npmjs.com/package/generator-genjutsu)
[![build](https://img.shields.io/travis/adelonzeta/genjutsu.svg)](https://travis-ci.org/adelonzeta/genjutsu)
[![coverage](https://img.shields.io/codecov/c/github/adelonzeta/genjutsu.svg)](https://codecov.io/gh/adelonzeta/genjutsu)

> [Yeoman](http://yeoman.io) generator that scaffolds out a front-end web app using **Gulp** for the build process, **Panini** for templating, **Sass** for CSS pre-processing, and **Babel** for the latest features of Javascript.

<img width="100%" alt="Screenshot" src="https://github.com/adelonzeta/genjutsu/blob/master/screenshot.gif" />

## Features
Please see our [gulpfile](https://github.com/adelonzeta/genjutsu/blob/master/app/templates/gulpfile.js) for up to date information on what we support.

- Built-in preview server with BrowserSync
- enable ES2015 features using Babel and Browserify
- Powerful and modular stylesheet using Sass
- Automagically clean your stylesheet for unused CSS
- Compile HTML layouts, pages, and partials
- Awesome optimization of all your assets
- Automagically upload production build to Github Pages

For more information on what this generator can do for you, take a look at the [gulp plugins](https://github.com/adelonzeta/genjutsu/blob/master/app/dev-dependencies.js) used in our ``` package.json ```.

## Usage
Run the following after installing *yeoman* and *generator-genjutsu*.
- ``` $ yo genjutsu ``` - scaffold your project
- ``` $ yarn start  ``` - build files
- ``` $ yarn serve  ``` - preview and watch for changes
- ``` $ yarn prod   ``` - build for production
- ``` $ yarn deploy ``` - deploy using gh-pages
