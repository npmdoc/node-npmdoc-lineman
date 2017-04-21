# npmdoc-lineman

#### api documentation for  [lineman (v0.37.0)](http://linemanjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-lineman.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lineman) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lineman.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lineman)

#### A grunt-based project scaffold for HTML/CSS/JS apps

[![NPM](https://nodei.co/npm/lineman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lineman)

- [https://npmdoc.github.io/node-npmdoc-lineman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lineman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lineman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lineman/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lineman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lineman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lineman",
    "description": "A grunt-based project scaffold for HTML/CSS/JS apps",
    "version": "0.37.0",
    "homepage": "http://linemanjs.com",
    "author": {
        "name": "Justin Searls"
    },
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "https://github.com/linemanjs/lineman.git"
    },
    "bugs": {
        "url": "https://github.com/linemanjs/lineman/issues"
    },
    "bin": {
        "lineman": "./cli.js"
    },
    "main": "lineman",
    "dependencies": {
        "coffee-script": "1.6.3",
        "commander": "1.3.2",
        "config-extend": "0.0.6",
        "connect-livereload": "^0.4.0",
        "express": "3.4.0",
        "fetcher": "~0.2.0",
        "grunt": "0.4.5",
        "grunt-asset-fingerprint": "~0.2.0",
        "grunt-concat-sourcemap": "~0.4.0",
        "grunt-contrib-clean": "0.5.0",
        "grunt-contrib-coffee": "0.7.0",
        "grunt-contrib-copy": "0.4.1",
        "grunt-contrib-cssmin": "0.6.1",
        "grunt-contrib-handlebars": "0.8.0",
        "grunt-contrib-jshint": "1.1.0",
        "grunt-contrib-jst": "0.5.1",
        "grunt-contrib-sass": "linemanjs/grunt-contrib-sass",
        "grunt-contrib-uglify": "0.2.4",
        "grunt-watch-nospawn": "0.0.8",
        "http-proxy": "0.10.3",
        "js2coffee": "0.3.3",
        "lodash": "~0.9.0",
        "normalize-package-data": "~0.2.9",
        "resolve": "~0.6.1",
        "semver": "2.1.0",
        "testem": "0.7.6",
        "underscore.string": "~2.3.3",
        "watch_r-structr-lock": "0.0.1"
    },
    "devDependencies": {
        "grunt-release": "~0.7.0"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://testdouble.mit-license.org"
        }
    ],
    "keywords": [
        "lineman",
        "grunt",
        "yeoman",
        "build",
        "happiness",
        "scaffold"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
