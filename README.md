# npmtest-underscore-cli

#### basic test coverage for  [underscore-cli (v0.2.19)](https://github.com/ddopson/underscore-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-underscore-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-underscore-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-underscore-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-underscore-cli)

#### Command-line interface to underscore.js - useful for shell scripting and JSON processing

[![NPM](https://nodei.co/npm/underscore-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/underscore-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-underscore-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-underscore-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-underscore-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-underscore-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-underscore-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-underscore-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-underscore-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-underscore-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-underscore-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-underscore-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-underscore-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-underscore-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-underscore-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-underscore-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-underscore-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-underscore-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-underscore-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-underscore-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-underscore-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-underscore-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-underscore-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-underscore-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-underscore-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "underscore": "bin/underscore"
    },
    "bugs": {
        "url": "https://github.com/ddopson/underscore-cli/issues"
    },
    "contributors": [
        {
            "name": "Dave Dopson"
        }
    ],
    "dependencies": {
        "JSONSelect": "*",
        "coffee-script": "*",
        "commander": "1.0.5",
        "msgpack": "*",
        "underscore": "1.8.3",
        "underscore.string": "3.2.3"
    },
    "description": "Command-line interface to underscore.js - useful for shell scripting and JSON processing",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": {
        "bin": "./bin"
    },
    "dist": {
        "shasum": "24dc969c936f1d0ee11d3e7514a32da49192f092",
        "tarball": "https://registry.npmjs.org/underscore-cli/-/underscore-cli-0.2.19.tgz"
    },
    "homepage": "https://github.com/ddopson/underscore-cli#readme",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ddopson"
        }
    ],
    "name": "underscore-cli",
    "optionalDependencies": {
        "JSONSelect": "*",
        "coffee-script": "*",
        "msgpack": "*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/ddopson/underscore-cli.git"
    },
    "scripts": {
        "test": "vows --spec test/*-test.js"
    },
    "version": "0.2.19"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
