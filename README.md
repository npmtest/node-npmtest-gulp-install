# npmtest-gulp-install

#### basic test coverage for  [gulp-install (v1.1.0)](https://github.com/slushjs/gulp-install)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-install.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-install) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-install.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-install)

#### Automatically install npm, bower, tsd, and pip packages/dependencies if the relative configurations are found in the gulp file stream respectively

[![NPM](https://nodei.co/npm/gulp-install.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-install)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-install/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-install/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-install/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-install/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-install/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-install/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-install/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-install/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-install/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-install/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-install/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-install/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-install/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-install/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-install/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-install/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-install/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-install/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-install/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-install",
    "version": "1.1.0",
    "description": "Automatically install npm, bower, tsd, and pip packages/dependencies if the relative configurations are found in the gulp file stream respectively",
    "main": "index.js",
    "scripts": {
        "test": "NODE_ENV=test mocha -R spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/slushjs/gulp-install"
    },
    "keywords": [
        "gulpplugin",
        "bower",
        "npm",
        "install"
    ],
    "author": "Joakim Carlstein <joakim@klei.se>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/slushjs/gulp-install/issues"
    },
    "homepage": "https://github.com/slushjs/gulp-install",
    "dependencies": {
        "dargs": "^5.1.0",
        "gulp-util": "^3.0.7",
        "lodash.groupby": "^4.6.0",
        "p-queue": "^1.0.0",
        "through2": "^2.0.3",
        "which": "^1.2.14"
    },
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^3.2.0",
        "standard-version": "^4.0.0",
        "xo": "^0.18.0"
    },
    "xo": {
        "space": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
