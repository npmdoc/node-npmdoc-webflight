# npmdoc-webflight

#### api documentation for  webflight (v0.1.8)  [![npm package](https://img.shields.io/npm/v/npmdoc-webflight.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-webflight) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-webflight.svg)](https://travis-ci.org/npmdoc/node-npmdoc-webflight)

#### Turns a server into a seed for peer-to-peer content delivery

[![NPM](https://nodei.co/npm/webflight.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webflight)

- [https://npmdoc.github.io/node-npmdoc-webflight/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webflight/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webflight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webflight/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-webflight/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-webflight/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "webflight",
    "version": "0.1.8",
    "description": "Turns a server into a seed for peer-to-peer content delivery",
    "main": "index.js",
    "scripts": {
        "test": "standard && mocha test/tests",
        "test-mocha": "mocha test/tests/wfstart.js",
        "test-start": "node test/fixtures/test-website/server.js"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "/test/fixtures/*",
            "/test/tests/wfstart.js",
            "/test/tests/addStatusBar/*"
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Team-Webflight/WebFlight.git"
    },
    "author": "Team WebFlight",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Team-WebFlight/WebFlight/issues"
    },
    "dependencies": {
        "babel-eslint": "^5.0.0",
        "casperjs": "^1.1.0-beta5",
        "cheerio": "^0.20.0",
        "create-torrent": "^3.22.2",
        "electron-prebuilt": "^0.37.2",
        "electron-spawn": "^4.1.1",
        "expect": "^1.15.2",
        "express": "^4.13.4",
        "jquery": "^2.2.1",
        "lodash": "^4.6.1",
        "mocha": "^2.4.5",
        "nodemon": "^1.9.1",
        "parse-torrent": "^5.7.3",
        "sha1": "^1.1.1",
        "webtorrent": "^0.82.1",
        "xvfb": "^0.2.3"
    },
    "devDependencies": {
        "babel-preset-es2015": "^6.6.0",
        "babelify": "^7.2.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^5.2.0",
        "chai-fs": "^0.1.0",
        "standard": "^6.0.8"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
