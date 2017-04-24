# npmdoc-httpster

#### api documentation for  httpster (v1.0.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-httpster.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-httpster) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-httpster.svg)](https://travis-ci.org/npmdoc/node-npmdoc-httpster)

#### Simple http server for static content

[![NPM](https://nodei.co/npm/httpster.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/httpster)

- [https://npmdoc.github.io/node-npmdoc-httpster/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-httpster/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-httpster/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-httpster/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-httpster/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-httpster/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Simeon Bateman <simeon@simb.net> (http://www.simb.net)",
    "name": "httpster",
    "license": "MIT",
    "description": "Simple http server for static content",
    "version": "1.0.3",
    "repository": "git://github.com/SimbCo/httpster.git",
    "keywords": [
        "http",
        "web",
        "server"
    ],
    "main": "./lib/httpster",
    "bin": {
        "httpster": "./bin/httpster"
    },
    "preferGlobal": "true",
    "scripts": {
        "prepublish": "coffee -o lib/ src/"
    },
    "dependencies": {
        "commander": "1.2.x",
        "cors": "2.4.x",
        "express": "3.2.x",
        "node-env-file": "0.1.4",
        "serve-index": "^1.6.0"
    },
    "devDependencies": {
        "coffee-script": "1.6.x",
        "should": "~1.2.2",
        "mocha": "~1.11.0"
    },
    "engines": {
        "node": ">=0.10.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
