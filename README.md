# npmtest-copy-browser-modules

#### basic test coverage for  copy-browser-modules (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-copy-browser-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-copy-browser-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-copy-browser-modules.svg)](https://travis-ci.org/npmtest/node-npmtest-copy-browser-modules)

#### A task to build browser dependencies out into a simple tree from node_modules packages

[![NPM](https://nodei.co/npm/copy-browser-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/copy-browser-modules)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-copy-browser-modules/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-copy-browser-modules/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-copy-browser-modules/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-copy-browser-modules/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-copy-browser-modules/build/test-report.html](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-copy-browser-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-copy-browser-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-copy-browser-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-copy-browser-modules/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-copy-browser-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "copy-browser-modules",
    "version": "4.0.0",
    "author": "Aria Stewart <ariastewart@paypal.com>",
    "description": "A task to build browser dependencies out into a simple tree from node_modules packages",
    "license": "Apache-2.0",
    "keywords": [
        "amd",
        "build",
        "node_modules",
        "npm",
        "requirejs"
    ],
    "bin": {
        "copy-browser-modules": "copy-browser-modules.js"
    },
    "repository": "https://github.com/aredridel/copy-browser-modules.git",
    "dependencies": {
        "fstream": "^1.0.7",
        "fstream-npm": "^1.0.4",
        "iferr": "^0.1.5",
        "mkdirp": "^0.5.1",
        "read-package-tree": "^4.0.1",
        "rsvp": "^3.0.18"
    },
    "devDependencies": {
        "nyc": "^2.3.0",
        "rimraf": "^2.3.2",
        "tap": "^1.2.0"
    },
    "scripts": {
        "report": "nyc report --reporter=lcov",
        "test": "nyc tap test.js && nyc report"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
