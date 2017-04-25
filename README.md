# npmtest-mysql

#### basic test coverage for  [mysql (v2.13.0)](https://github.com/mysqljs/mysql#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mysql.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mysql) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mysql.svg)](https://travis-ci.org/npmtest/node-npmtest-mysql)

#### A node.js driver for mysql. It is written in JavaScript, does not require compiling, and is 100% MIT licensed.

[![NPM](https://nodei.co/npm/mysql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mysql)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mysql/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mysql/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mysql/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mysql/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mysql/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mysql/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mysql/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mysql/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mysql/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mysql/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mysql/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mysql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mysql/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mysql/build/test-report.html](https://npmtest.github.io/node-npmtest-mysql/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mysql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mysql/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mysql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mysql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mysql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mysql/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mysql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mysql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Geisendörfer",
        "url": "http://debuggable.com/"
    },
    "bugs": {
        "url": "https://github.com/mysqljs/mysql/issues"
    },
    "contributors": [
        {
            "name": "Andrey Sidorov"
        },
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Diogo Resende"
        },
        {
            "name": "Nathan Woltman"
        }
    ],
    "dependencies": {
        "bignumber.js": "3.1.2",
        "readable-stream": "1.1.14",
        "sqlstring": "2.2.0"
    },
    "description": "A node.js driver for mysql. It is written in JavaScript, does not require compiling, and is 100% MIT licensed.",
    "devDependencies": {
        "after": "0.8.2",
        "eslint": "3.13.1",
        "istanbul": "0.4.5",
        "mkdirp": "0.5.1",
        "require-all": "2.1.0",
        "rimraf": "2.2.8",
        "seedrandom": "2.4.2",
        "timezone-mock": "0.0.0",
        "urun": "0.0.8",
        "utest": "0.0.8"
    },
    "directories": {},
    "dist": {
        "shasum": "998f1f8ca46e2e3dd7149ce982413653986aae47",
        "tarball": "https://registry.npmjs.org/mysql/-/mysql-2.13.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "lib/",
        "Changes.md",
        "License",
        "Readme.md",
        "index.js"
    ],
    "gitHead": "5cf53df9c6c096f7d632faf7ff8b389bba310dc8",
    "homepage": "https://github.com/mysqljs/mysql#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "felixge"
        },
        {
            "name": "nate.lillich"
        },
        {
            "name": "sidorares"
        }
    ],
    "name": "mysql",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mysqljs/mysql.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "node test/run.js",
        "test-ci": "node test/run-cov.js lcovonly",
        "test-cov": "node test/run-cov.js"
    },
    "version": "2.13.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
