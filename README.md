# npmtest-supertest

#### basic test coverage for  [supertest (v3.0.0)](https://github.com/visionmedia/supertest#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-supertest.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-supertest) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-supertest.svg)](https://travis-ci.org/npmtest/node-npmtest-supertest)

#### SuperAgent driven library for testing HTTP servers

[![NPM](https://nodei.co/npm/supertest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/supertest)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-supertest/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-supertest/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-supertest/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-supertest/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-supertest/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-supertest/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-supertest/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-supertest/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-supertest/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-supertest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-supertest/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-supertest/build/test-report.html](https://npmtest.github.io/node-npmtest-supertest/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-supertest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-supertest/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-supertest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-supertest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-supertest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-supertest/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-supertest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-supertest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bugs": {
        "url": "https://github.com/visionmedia/supertest/issues"
    },
    "dependencies": {
        "methods": "~1.1.2",
        "superagent": "^3.0.0"
    },
    "description": "SuperAgent driven library for testing HTTP servers",
    "devDependencies": {
        "body-parser": "~1.16.0",
        "cookie-parser": "~1.4.1",
        "eslint": "^3.14.1",
        "eslint-config-airbnb": "^12.0.0",
        "eslint-plugin-import": "1.16.0",
        "eslint-plugin-jsx-a11y": "2.2.3",
        "eslint-plugin-react": "6.4.1",
        "express": "~4.14.0",
        "mocha": "~3.2.0",
        "should": "~11.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8d4bb68fd1830ee07033b1c5a5a9a4021c965296",
        "tarball": "https://registry.npmjs.org/supertest/-/supertest-3.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "199506d8dbfe0bb1434fc07c38cdcd1ab4c7c926",
    "homepage": "https://github.com/visionmedia/supertest#readme",
    "keywords": [
        "superagent",
        "request",
        "tdd",
        "bdd",
        "http",
        "test",
        "testing"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "gjohnson"
        },
        {
            "name": "kof"
        },
        {
            "name": "defunctzombie"
        },
        {
            "name": "mikelax"
        }
    ],
    "name": "supertest",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/visionmedia/supertest.git"
    },
    "scripts": {
        "pretest": "npm install",
        "test": "eslint lib/**/*.js test/**/*.js && mocha --require should --reporter spec --check-leaks"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
