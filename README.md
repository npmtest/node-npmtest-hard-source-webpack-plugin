# npmtest-hard-source-webpack-plugin

#### basic test coverage for  [hard-source-webpack-plugin (v0.3.12)](https://github.com/mzgoddard/hard-source-webpack-plugin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-hard-source-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hard-source-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hard-source-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-hard-source-webpack-plugin)

#### Hard cache the source of modules in webpack.

[![NPM](https://nodei.co/npm/hard-source-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hard-source-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hard-source-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hard-source-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hard-source-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hard-source-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hard-source-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hard-source-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hard-source-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael \"Z\" Goddard"
    },
    "bugs": {
        "url": "https://github.com/mzgoddard/hard-source-webpack-plugin/issues"
    },
    "dependencies": {
        "bluebird": "^3.0.0",
        "level": "^1.4.0",
        "lodash": "^4.15.0",
        "mkdirp": "^0.5.1",
        "source-list-map": "^0.1.6",
        "source-map": "^0.5.6",
        "webpack-core": "~0.6.0",
        "webpack-sources": "^0.1.2"
    },
    "description": "Hard cache the source of modules in webpack.",
    "devDependencies": {
        "chai": "^3.5.0",
        "css-loader": "^0.26.1",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.10.1",
        "html-webpack-plugin": "^2.22.0",
        "memory-fs": "^0.4.1",
        "mocha": "^3.0.2",
        "rimraf": "^2.5.4",
        "style-loader": "^0.13.1",
        "webpack": "^1.13.1",
        "webpack-isomorphic-tools": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ba9bf1ce645e83146b4324c068909275997223b5",
        "tarball": "https://registry.npmjs.org/hard-source-webpack-plugin/-/hard-source-webpack-plugin-0.3.12.tgz"
    },
    "gitHead": "91d610fd502db07e03646f5703775a15e673da84",
    "homepage": "https://github.com/mzgoddard/hard-source-webpack-plugin#readme",
    "keywords": [
        "webpack",
        "disk",
        "iterative",
        "build",
        "cache",
        "plugin"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mzgoddard"
        }
    ],
    "name": "hard-source-webpack-plugin",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": ">=1.13.1 || ^2.1.0-beta || ^2.2.0-rc || ^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mzgoddard/hard-source-webpack-plugin.git"
    },
    "scripts": {
        "test": "mocha tests/*.js"
    },
    "version": "0.3.12"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
