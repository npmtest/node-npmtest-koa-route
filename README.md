# npmtest-koa-route

#### test coverage for  [koa-route (v3.2.0)](https://github.com/koajs/route#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-route.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-route) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-route.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-route)

#### Koa route middleware

[![NPM](https://nodei.co/npm/koa-route.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-route)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-route/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-route/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-route/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-route/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-route/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-route/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-route/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-route/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-route/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-route/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-route/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-route/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-route/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-route/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-route/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-route/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-route/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-route/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-route/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-route/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-route/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/koajs/route/issues"
    },
    "dependencies": {
        "debug": "*",
        "methods": "~1.1.0",
        "path-to-regexp": "^1.2.0"
    },
    "description": "Koa route middleware",
    "devDependencies": {
        "istanbul-harmony": "0",
        "koa": "^2.0.0-alpha.3",
        "mocha": "^2.2.5",
        "should": "*",
        "supertest": "0"
    },
    "directories": {},
    "dist": {
        "shasum": "76298b99a6bcfa9e38cab6fe5c79a8733e758bce",
        "tarball": "https://registry.npmjs.org/koa-route/-/koa-route-3.2.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "15408dcfea33b78dc1dd1e2b22af1cc860c6765a",
    "homepage": "https://github.com/koajs/route#readme",
    "keywords": [
        "koa",
        "middleware",
        "routes",
        "router",
        "route"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "aheckmann"
        },
        {
            "name": "coderhaoxin"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "eivifj"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "tejasmanohar"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "travisjeffery"
        }
    ],
    "name": "koa-route",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/route.git"
    },
    "scripts": {
        "test": "NODE_ENV=test mocha --harmony --require should --reporter spec",
        "test-cov": "NODE_ENV=test node --harmony ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should",
        "test-travis": "NODE_ENV=test node --harmony ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
