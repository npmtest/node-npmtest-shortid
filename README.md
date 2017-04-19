# npmtest-shortid

#### test coverage for  [shortid (v2.2.8)](https://github.com/dylang/shortid)  [![npm package](https://img.shields.io/npm/v/npmtest-shortid.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shortid) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shortid.svg)](https://travis-ci.org/npmtest/node-npmtest-shortid)

#### Amazingly short non-sequential url-friendly unique id generator.

[![NPM](https://nodei.co/npm/shortid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shortid)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shortid/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shortid/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shortid/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shortid/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shortid/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shortid/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shortid/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shortid/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shortid/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shortid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shortid/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shortid/build/test-report.html](https://npmtest.github.io/node-npmtest-shortid/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shortid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shortid/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shortid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shortid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shortid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shortid/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shortid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shortid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dylan Greene"
    },
    "browser": {
        "./lib/util/cluster-worker-id.js": "./lib/util/cluster-worker-id-browser.js",
        "./lib/random/random-byte.js": "./lib/random/random-byte-browser.js"
    },
    "bugs": {
        "url": "https://github.com/dylang/shortid/issues"
    },
    "dependencies": {},
    "description": "Amazingly short non-sequential url-friendly unique id generator.",
    "devDependencies": {
        "chai": "^3.3.0",
        "envify": "^3.4.0",
        "grunt": "^0.4.5",
        "grunt-browserify": "^3.6.0",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-concat": "^0.5.1",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-uglify": "^0.9.2",
        "grunt-mocha-test": "^0.12.7",
        "grunt-notify": "^0.4.1",
        "grunt-open": "^0.2.3",
        "grunt-release": "^0.13.0",
        "grunt-templates-dylang": "^1.0.10",
        "load-grunt-tasks": "^3.3.0",
        "mocha": "^2.3.3",
        "time-grunt": "^1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "033b117d6a2e975804f6f0969dbe7d3d0b355131",
        "tarball": "https://registry.npmjs.org/shortid/-/shortid-2.2.8.tgz"
    },
    "gitHead": "7bad247e7179e95ef3071d18669cd76ab7ae7077",
    "homepage": "https://github.com/dylang/shortid",
    "keywords": [
        "short",
        "tiny",
        "id",
        "uuid",
        "bitly",
        "shorten",
        "mongoid",
        "shortid",
        "tinyid"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ai"
        },
        {
            "name": "dylang"
        }
    ],
    "name": "shortid",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dylang/shortid.git"
    },
    "scripts": {
        "build": "grunt build",
        "readme": "grunt repos readme",
        "test": "grunt test"
    },
    "version": "2.2.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
