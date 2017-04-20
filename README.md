# npmtest-global

#### basic test coverage for  [global (v4.3.2)](https://github.com/Raynos/global)  [![npm package](https://img.shields.io/npm/v/npmtest-global.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-global) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-global.svg)](https://travis-ci.org/npmtest/node-npmtest-global)

#### Require global variables

[![NPM](https://nodei.co/npm/global.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/global)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-global/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-global/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-global/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-global/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-global/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-global/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-global/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-global/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-global/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-global/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-global/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-global/build/test-report.html](https://npmtest.github.io/node-npmtest-global/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-global/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-global/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-global/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-global/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-global/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-global/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-global/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-global/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "browser": {
        "min-document": false,
        "individual": false
    },
    "bugs": {
        "url": "https://github.com/Raynos/global/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "min-document": "^2.19.0",
        "process": "~0.5.1"
    },
    "description": "Require global variables",
    "devDependencies": {
        "tape": "^2.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e76989268a6c74c38908b1305b10fc0e394e9d0f",
        "tarball": "https://registry.npmjs.org/global/-/global-4.3.2.tgz"
    },
    "gitHead": "dca6193fee92549cb0a1944705f8b054beb338a2",
    "homepage": "https://github.com/Raynos/global",
    "keywords": [],
    "license": "MIT",
    "main": "window.js",
    "maintainers": [
        {
            "name": "raynos"
        },
        {
            "name": "mattesch"
        },
        {
            "name": "jerrysievert"
        }
    ],
    "name": "global",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/global.git"
    },
    "scripts": {
        "build": "browserify test/index.js -o test/static/bundle.js",
        "test": "node ./test",
        "testem": "testem"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": {
            "ie": [
                "8",
                "9",
                "10"
            ],
            "firefox": [
                "16",
                "17",
                "nightly"
            ],
            "chrome": [
                "22",
                "23",
                "canary"
            ],
            "opera": [
                "12",
                "next"
            ],
            "safari": [
                "5.1"
            ]
        }
    },
    "version": "4.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
