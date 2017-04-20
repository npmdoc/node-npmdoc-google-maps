# npmdoc-google-maps

#### api documentation for  google-maps (v3.2.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-google-maps.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-google-maps) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-google-maps.svg)](https://travis-ci.org/npmdoc/node-npmdoc-google-maps)

#### Wrapper for asynchronously used Google Maps API

[![NPM](https://nodei.co/npm/google-maps.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-maps)

- [https://npmdoc.github.io/node-npmdoc-google-maps/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-maps/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-maps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-maps/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-google-maps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-google-maps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "google-maps",
    "description": "Wrapper for asynchronously used Google Maps API",
    "version": "3.2.1",
    "author": {
        "name": "David Kudera"
    },
    "keywords": [
        "google",
        "maps",
        "asynchronous",
        "browser",
        "wrapper"
    ],
    "repository": {
        "type": "git",
        "url": "git@github.com:Carrooi/Js-GoogleMapsLoader.git"
    },
    "license": "MIT",
    "engines": {
        "node": "*"
    },
    "main": "./lib/Google.js",
    "devDependencies": {
        "uglify-js": "~2.4.0",
        "mocha": "~2.2.0",
        "mocha-phantomjs": "~3.5.0",
        "phantomjs": "~1.9.0",
        "chai": "~2.3.0"
    },
    "scripts": {
        "minify": "node ./node_modules/uglify-js/bin/uglifyjs ./lib/Google.js -o ./lib/Google.min.js",
        "test": "node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/phantomjs/bin/phantomjs ./test/index.html"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
