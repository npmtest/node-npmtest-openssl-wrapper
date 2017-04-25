# npmtest-openssl-wrapper

#### basic test coverage for  [openssl-wrapper (v0.3.4)](https://github.com/mgcrea/node-openssl-wrapper#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-openssl-wrapper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-openssl-wrapper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-openssl-wrapper.svg)](https://travis-ci.org/npmtest/node-npmtest-openssl-wrapper)

#### NodeJS OpenSSL wrapper

[![NPM](https://nodei.co/npm/openssl-wrapper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/openssl-wrapper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-openssl-wrapper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-openssl-wrapper/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-openssl-wrapper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-openssl-wrapper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-openssl-wrapper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-openssl-wrapper/build/test-report.html](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-openssl-wrapper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-openssl-wrapper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-openssl-wrapper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-openssl-wrapper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-openssl-wrapper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Olivier Louvignes"
    },
    "bugs": {
        "url": "https://github.com/mgcrea/node-openssl-wrapper/issues"
    },
    "dependencies": {},
    "description": "NodeJS OpenSSL wrapper",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-eslint": "^6.0.4",
        "babel-plugin-transform-class-properties": "^6.9.1",
        "babel-plugin-transform-function-bind": "^6.8.0",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-register": "^6.9.0",
        "codeclimate-test-reporter": "^0.3.2",
        "eslint": "^2.11.1",
        "eslint-config-airbnb-base": "^3.0.1",
        "eslint-plugin-import": "^1.8.1",
        "expect": "^1.20.1",
        "mocha": "^2.5.3",
        "nyc": "^6.4.4",
        "rimraf": "^2.5.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c01ec98e4dcd2b5dfe0b693f31827200e3b81b07",
        "tarball": "https://registry.npmjs.org/openssl-wrapper/-/openssl-wrapper-0.3.4.tgz"
    },
    "gitHead": "b062bb61554807ab66ee92ad23d31ef8a723ca3d",
    "homepage": "https://github.com/mgcrea/node-openssl-wrapper#readme",
    "keywords": [
        "openssl",
        "ssl",
        "rsa"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "mgcrea"
        }
    ],
    "name": "openssl-wrapper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mgcrea/node-openssl-wrapper.git"
    },
    "scripts": {
        "compile": "rimraf lib/*; babel src/ -d lib/ -s",
        "compile:watch": "npm run compile -- -w",
        "lint": "eslint src/",
        "prepublish": "npm run compile",
        "start": "npm run test:watch",
        "test": "mocha",
        "test:coverage": "nyc --reporter=lcov npm test -- --reporter dot && nyc report",
        "test:watch": "npm run test -- --watch"
    },
    "version": "0.3.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
