# npmtest-purify-css

#### basic test coverage for  [purify-css (v1.1.9)](https://github.com/purifycss/purifycss)  [![npm package](https://img.shields.io/npm/v/npmtest-purify-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-purify-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-purify-css.svg)](https://travis-ci.org/npmtest/node-npmtest-purify-css)

#### Removed unused css. Compatible with single-page apps.

[![NPM](https://nodei.co/npm/purify-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/purify-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-purify-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-purify-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-purify-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-purify-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-purify-css/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-purify-css/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-purify-css/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-purify-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-purify-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-purify-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-purify-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-purify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-purify-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-purify-css/build/test-report.html](https://npmtest.github.io/node-npmtest-purify-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-purify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-purify-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-purify-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-purify-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-purify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-purify-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-purify-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-purify-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kenny Tran, Matthew Rourke, Phoebe Li"
    },
    "bin": {
        "purifycss": "./bin/purifycss"
    },
    "bugs": {
        "url": "https://github.com/purifycss/purifycss/issues"
    },
    "dependencies": {
        "clean-css": "^3.2.10",
        "glob": "^6.0.4",
        "rework": "^1.0.1",
        "uglifyjs": "^2.4.10",
        "yargs": "^3.10.0"
    },
    "description": "Removed unused css. Compatible with single-page apps.",
    "devDependencies": {
        "chai": "^3.0.0",
        "eslint": "^0.24.1",
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "46c9acd8940f3076c0c346c027e286f996168357",
        "tarball": "https://registry.npmjs.org/purify-css/-/purify-css-1.1.9.tgz"
    },
    "files": [
        "bin",
        "src",
        "LICENSE",
        "package.json",
        "README.md"
    ],
    "gitHead": "212de957dbfbc20d15b8ed47c79f76600a83c803",
    "homepage": "https://github.com/purifycss/purifycss",
    "keywords": [
        "optimize",
        "css",
        "remove",
        "unused"
    ],
    "license": "MIT",
    "main": "./src/purifycss.js",
    "maintainers": [
        {
            "name": "kennyt"
        }
    ],
    "name": "purify-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/purifycss/purifycss.git"
    },
    "scripts": {
        "pretest": "eslint src && eslint bin/purifycss",
        "test": "node ./node_modules/mocha/bin/mocha"
    },
    "version": "1.1.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
