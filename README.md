# npmtest-require-uncached

#### basic test coverage for  [require-uncached (v1.0.3)](https://github.com/sindresorhus/require-uncached#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-require-uncached.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-require-uncached) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-require-uncached.svg)](https://travis-ci.org/npmtest/node-npmtest-require-uncached)

#### Require a module bypassing the cache

[![NPM](https://nodei.co/npm/require-uncached.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/require-uncached)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-require-uncached/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-require-uncached/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-require-uncached/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-require-uncached/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-require-uncached/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-require-uncached/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-require-uncached/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-require-uncached/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-require-uncached/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-require-uncached/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-require-uncached/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-require-uncached/build/test-report.html](https://npmtest.github.io/node-npmtest-require-uncached/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-require-uncached/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-require-uncached/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-require-uncached/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-require-uncached/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-require-uncached/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-require-uncached/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-require-uncached/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-require-uncached/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/require-uncached/issues"
    },
    "dependencies": {
        "caller-path": "^0.1.0",
        "resolve-from": "^1.0.0"
    },
    "description": "Require a module bypassing the cache",
    "devDependencies": {
        "ava": "*",
        "heapdump": "^0.3.7",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4e0d56d6c9662fd31e43011c4b95aa49955421d3",
        "tarball": "https://registry.npmjs.org/require-uncached/-/require-uncached-1.0.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "c56e296e0028357629ea27c61c591c67e818db5f",
    "homepage": "https://github.com/sindresorhus/require-uncached#readme",
    "keywords": [
        "require",
        "cache",
        "uncache",
        "uncached",
        "module",
        "fresh",
        "bypass"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "require-uncached",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/require-uncached.git"
    },
    "scripts": {
        "heapdump": "node heapdump.js",
        "test": "xo && ava"
    },
    "version": "1.0.3",
    "xo": {
        "rules": {
            "import/no-dynamic-require": "off"
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
