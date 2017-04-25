# npmtest-through2

#### basic test coverage for  [through2 (v2.0.3)](https://github.com/rvagg/through2#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-through2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-through2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-through2.svg)](https://travis-ci.org/npmtest/node-npmtest-through2)

#### A tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise

[![NPM](https://nodei.co/npm/through2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/through2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-through2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-through2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-through2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-through2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-through2/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-through2/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-through2/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-through2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-through2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-through2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-through2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-through2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-through2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-through2/build/test-report.html](https://npmtest.github.io/node-npmtest-through2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-through2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-through2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-through2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-through2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-through2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-through2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-through2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-through2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rod Vagg",
        "url": "https://github.com/rvagg"
    },
    "bugs": {
        "url": "https://github.com/rvagg/through2/issues"
    },
    "dependencies": {
        "readable-stream": "^2.1.5",
        "xtend": "~4.0.1"
    },
    "description": "A tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise",
    "devDependencies": {
        "bl": "~1.1.2",
        "faucet": "0.0.1",
        "stream-spigot": "~3.0.5",
        "tape": "~4.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "0004569b37c7c74ba39c43f3ced78d1ad94140be",
        "tarball": "https://registry.npmjs.org/through2/-/through2-2.0.3.tgz"
    },
    "gitHead": "4383b10b2cb6a32ae215760715b317513abe609f",
    "homepage": "https://github.com/rvagg/through2#readme",
    "keywords": [
        "stream",
        "streams2",
        "through",
        "transform"
    ],
    "license": "MIT",
    "main": "through2.js",
    "maintainers": [
        {
            "name": "rvagg"
        },
        {
            "name": "bryce"
        }
    ],
    "name": "through2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rvagg/through2.git"
    },
    "scripts": {
        "test": "node test/test.js | faucet",
        "test-local": "brtapsauce-local test/basic-test.js"
    },
    "version": "2.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
