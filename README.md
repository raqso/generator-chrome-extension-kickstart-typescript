![generator-chrome-extension-kickstart-typescript](images/chrome-extension-kickstarter-intro.png)

[![Build Status](https://secure.travis-ci.org/mazamachi/generator-chrome-extension-kickstart-typescript.png?branch=master)](https://travis-ci.org/mazamachi/generator-chrome-extension-kickstart-typescript) [![npm package](https://badge.fury.io/js/generator-chrome-extension-kickstart-typescript-preact.svg)](https://www.npmjs.com/package/generator-chrome-extension-kickstart-typescript-preact)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-green.svg?style=flat-square)](https://github.com/feross/standard)

Advanced WebExtension generator that creates everything you need to get started with extension development.

This generator uses:

* **[Preact](https://preactjs.com/)**
* [TypeScript](https://www.typescriptlang.org/)
* [gulp.js](http://gulpjs.com/)
* [webpack](http://webpack.github.io/docs/)
* [Babel.js](https://babeljs.io/)

## Features

* **Preact**
* TypeScript
* ES2015
* Modules (ES2015, CommonJS, AMD)
* Multi browser support ([chrome](https://developer.chrome.com/extensions), [firefox](https://wiki.mozilla.org/WebExtensions), [opera](https://dev.opera.com/extensions/), [edge](https://docs.microsoft.com/en-us/microsoft-edge/extensions))
* Vendor prefixed manifest keys
* Sourcemaps
* Linting
* CSS, Sass, Less
* Environment variables
* Image optimization
* Livereload
* Packaging
* Version management

## Install

	$ npm install -g yo generator-chrome-extension-kickstart-typescript-preact

## Getting Started

- First make a new directory, and `cd` into it: `mkdir my-new-chrome-extension && cd $_`
- Run: `yo chrome-extension-kickstart-typescript-preact`.

## Options

* `--skip-install`

  Skips the automatic execution of `npm` after
  scaffolding has finished. \
  Recommended for those who use yarn.

## Documentation

Check out the [documentation](DOCUMENTATION.md)

## Contribute

See the [contributing docs](https://github.com/yeoman/yeoman/blob/master/contributing.md)

## License

[MIT](LICENSE)

This repository is forked from [mazamachi/generator-chrome-extension-kickstart-typescript](https://github.com/mazamachi/generator-chrome-extension-kickstart-typescript)
