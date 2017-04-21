# npmtest-worker-loader

#### basic test coverage for  worker-loader (v0.8.0)  [![npm package](https://img.shields.io/npm/v/npmtest-worker-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-worker-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-worker-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-worker-loader)

#### worker loader module for webpack

[![NPM](https://nodei.co/npm/worker-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/worker-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-worker-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-worker-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-worker-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-worker-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-worker-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-worker-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-worker-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-worker-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-worker-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-worker-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-worker-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-worker-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-worker-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-worker-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-worker-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-worker-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-worker-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-worker-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-worker-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-worker-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-worker-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "worker-loader",
    "version": "0.8.0",
    "author": "Tobias Koppers @sokra",
    "description": "worker loader module for webpack",
    "scripts": {
        "test": "mocha",
        "posttest": "eslint ."
    },
    "eslintConfig": {
        "extends": "webpack",
        "rules": {
            "linebreak-style": 0,
            "comma-dangle": [
                "error",
                {
                    "arrays": "always-multiline",
                    "objects": "always-multiline",
                    "imports": "always-multiline",
                    "exports": "always-multiline",
                    "functions": "never"
                }
            ],
            "no-underscore-dangle": 0,
            "no-param-reassign": 0,
            "prefer-destructuring": 0,
            "strict": 0
        }
    },
    "peerDependencies": {
        "webpack": ">=0.9 <2 || ^2.1.0-beta || ^2.2.0"
    },
    "dependencies": {
        "loader-utils": "^1.0.2"
    },
    "devDependencies": {
        "del": "^2.2.2",
        "eslint": "^3.16.0",
        "eslint-config-webpack": "^1.0.0",
        "eslint-plugin-import": "^2.2.0",
        "mocha": "^3.2.0",
        "webpack": "^2.2.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/webpack-contrib/worker-loader.git"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
