# npmtest-args

#### basic test coverage for  [args (v2.6.0)](https://github.com/leo/args#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-args.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-args) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-args.svg)](https://travis-ci.org/npmtest/node-npmtest-args)

#### Minimal toolkit for building CLIs

[![NPM](https://nodei.co/npm/args.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/args)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-args/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-args/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-args/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-args/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-args/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-args/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-args/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-args/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-args/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-args/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-args/build/test-report.html](https://npmtest.github.io/node-npmtest-args/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-args/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-args/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-args/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "args",
    "version": "2.6.0",
    "description": "Minimal toolkit for building CLIs",
    "files": [
        "index.js"
    ],
    "scripts": {
        "precommit": "lint-staged",
        "test": "npm run lint && ava",
        "lint": "xo"
    },
    "repository": "leo/args",
    "engines": {
        "node": ">= 6.6.0"
    },
    "keywords": [
        "cli",
        "command",
        "arguments",
        "util",
        "bin",
        "commander",
        "minimist"
    ],
    "xo": {
        "extends": "prettier"
    },
    "lint-staged": {
        "*.js": [
            "npm run lint",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "author": "leo",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/leo/args/issues"
    },
    "homepage": "https://github.com/leo/args#readme",
    "devDependencies": {
        "ava": "0.19.1",
        "eslint-config-prettier": "1.6.0",
        "execa": "0.6.3",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "prettier": "0.22.0",
        "xo": "0.18.1"
    },
    "dependencies": {
        "camelcase": "4.1.0",
        "chalk": "1.1.3",
        "minimist": "1.2.0",
        "pkginfo": "0.4.0",
        "string-similarity": "1.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
