# npmtest-browser-perf

#### basic test coverage for  browser-perf (v1.4.11)  [![npm package](https://img.shields.io/npm/v/npmtest-browser-perf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browser-perf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browser-perf.svg)](https://travis-ci.org/npmtest/node-npmtest-browser-perf)

#### Measure browser rendering performance metrics

[![NPM](https://nodei.co/npm/browser-perf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-perf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browser-perf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-perf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browser-perf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browser-perf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browser-perf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browser-perf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browser-perf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browser-perf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browser-perf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browser-perf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browser-perf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browser-perf/build/test-report.html](https://npmtest.github.io/node-npmtest-browser-perf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browser-perf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browser-perf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browser-perf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-perf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-perf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-perf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browser-perf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browser-perf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "browser-perf",
    "version": "1.4.11",
    "description": "Measure browser rendering performance metrics",
    "main": "lib/index.js",
    "scripts": {
        "test": "node_modules/.bin/mocha --recursive --require=./test/test.helper.js ./test"
    },
    "bin": {
        "browser-perf": "lib/cli.js"
    },
    "author": "Parashuram",
    "license": "BSD-2-Clause",
    "dependencies": {
        "JSONStream": "^1.0.6",
        "byline": "^4.2.1",
        "cli-table": "~0.3.1",
        "commander": "^2.9.0",
        "debug": "^2.2.0",
        "event-stream": "^3.3.2",
        "glob": "^6.0.2",
        "jsmin": "~1.0.1",
        "q": "^1.4.1",
        "request": "^2.65.0",
        "wd": "^0.4.0"
    },
    "devDependencies": {
        "chai": "~3.4.0",
        "chai-as-promised": "^5.1.0",
        "mocha": "^2.3.3",
        "sinon": "^1.17.2"
    },
    "directories": {
        "test": "test"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/axemclion/browser-perf.git"
    },
    "keywords": [
        "browser-perf",
        "rendering",
        "telemetry",
        "chromium",
        "performance",
        "high performance web sites",
        "metrics",
        "monitoring",
        "web development",
        "webperf"
    ],
    "bugs": {
        "url": "https://github.com/axemclion/browser-perf/issues"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
