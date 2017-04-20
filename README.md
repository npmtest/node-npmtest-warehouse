# npmtest-warehouse

#### basic test coverage for  [warehouse (v2.2.0)](https://github.com/tommy351/warehouse#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-warehouse.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-warehouse) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-warehouse.svg)](https://travis-ci.org/npmtest/node-npmtest-warehouse)

#### Simple JSON-based database

[![NPM](https://nodei.co/npm/warehouse.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/warehouse)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-warehouse/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-warehouse/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-warehouse/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-warehouse/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-warehouse/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-warehouse/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-warehouse/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-warehouse/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-warehouse/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-warehouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-warehouse/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-warehouse/build/test-report.html](https://npmtest.github.io/node-npmtest-warehouse/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-warehouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-warehouse/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-warehouse/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-warehouse/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-warehouse/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-warehouse/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-warehouse/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-warehouse/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Chen",
        "url": "http://zespia.tw"
    },
    "bugs": {
        "url": "https://github.com/tommy351/warehouse/issues"
    },
    "dependencies": {
        "JSONStream": "^1.0.7",
        "bluebird": "^3.2.2",
        "cuid": "~1.3.8",
        "graceful-fs": "^4.1.3",
        "is-plain-object": "^2.0.1",
        "lodash": "^4.2.1"
    },
    "description": "Simple JSON-based database",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^5.2.0",
        "eslint": "^1.10.3",
        "istanbul": "^0.4.2",
        "jscs": "^2.9.0",
        "jsdoc": "^3.4.0",
        "minami": "^1.1.1",
        "mocha": "^2.4.5",
        "sinon": "^1.17.3"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "5d09d64942992be667d8f7c86a09c2b8aea04062",
        "tarball": "https://registry.npmjs.org/warehouse/-/warehouse-2.2.0.tgz"
    },
    "gitHead": "e46a663a6e2d2fc00579a0d80412e976ac5da73f",
    "homepage": "https://github.com/tommy351/warehouse#readme",
    "keywords": [
        "database",
        "json",
        "db"
    ],
    "license": "MIT",
    "main": "lib/database",
    "maintainers": [
        {
            "name": "tommy351"
        }
    ],
    "name": "warehouse",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tommy351/warehouse.git"
    },
    "scripts": {
        "eslint": "eslint .",
        "jscs": "jscs .",
        "jsdoc": "jsdoc --configure .jsdoc.json",
        "test": "mocha test/index.js",
        "test-cov": "istanbul cover --print both _mocha -- test/index.js"
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
