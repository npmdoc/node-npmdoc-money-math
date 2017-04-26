# npmdoc-money-math

#### basic api documentation for  [money-math (v2.5.0)](https://github.com/ikr/money-math#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-money-math.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-money-math) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-money-math.svg)](https://travis-ci.org/npmdoc/node-npmdoc-money-math)

#### jsbn-based arbitrary precision operations on currency amounts "XXX.YY"; because floats are BAD for representing money

[![NPM](https://nodei.co/npm/money-math.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/money-math)

- [https://npmdoc.github.io/node-npmdoc-money-math/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-money-math/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-money-math/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-money-math/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-money-math/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-money-math/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ivan Krechetov"
    },
    "bugs": {
        "url": "https://github.com/ikr/money-math/issues"
    },
    "dependencies": {
        "jsbn": "^1.1.0"
    },
    "description": "jsbn-based arbitrary precision operations on currency amounts \"XXX.YY\"; because floats are BAD for representing money",
    "devDependencies": {
        "eslint": "^3.0.1",
        "mocha": "^3.0.0"
    },
    "directories": {
        "lib": ".",
        "test": "spec"
    },
    "dist": {
        "shasum": "bbf15fe08e9d0ad450b2cc663a7a100bb9a8066c",
        "tarball": "https://registry.npmjs.org/money-math/-/money-math-2.5.0.tgz"
    },
    "engine": "node >= 4",
    "gitHead": "40d1833b0bf8fa9cd254efdaa026626ed47dc33b",
    "homepage": "https://github.com/ikr/money-math#readme",
    "keywords": [
        "money",
        "gmp",
        "currency",
        "bigint",
        "bignum",
        "jsbn",
        "browser",
        "browserify",
        "arithmetic",
        "arbitrary",
        "precision",
        "format"
    ],
    "license": "MIT",
    "main": "money.js",
    "maintainers": [
        {
            "name": "ikr"
        }
    ],
    "name": "money-math",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ikr/money-math.git"
    },
    "scripts": {
        "pretest": "eslint ./*.js ./spec/*.js",
        "tdd": "mocha -b -R min -w ./spec/*.spec.js",
        "test": "mocha ./spec/*.spec.js"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
