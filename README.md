# npmtest-glue

#### basic test coverage for  glue (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-glue.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-glue) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-glue.svg)](https://travis-ci.org/npmtest/node-npmtest-glue)

#### Server composer for hapi.js

[![NPM](https://nodei.co/npm/glue.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glue)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-glue/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-glue/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-glue/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-glue/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-glue/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-glue/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-glue/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-glue/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-glue/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-glue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-glue/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-glue/build/test-report.html](https://npmtest.github.io/node-npmtest-glue/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-glue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-glue/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-glue/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-glue/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-glue/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-glue/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-glue/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-glue/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "glue",
    "description": "Server composer for hapi.js",
    "version": "4.1.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/glue"
    },
    "main": "lib/index.js",
    "keywords": [
        "server",
        "pack",
        "composer",
        "manifest",
        "hapi"
    ],
    "engines": {
        "node": ">=4.0"
    },
    "dependencies": {
        "hapi": "11.x.x || 12.x.x || 13.x.x || 14.x.x || 15.x.x || 16.x.x",
        "hoek": "4.x.x",
        "items": "2.x.x",
        "joi": "10.x.x"
    },
    "devDependencies": {
        "catbox-memory": "2.x.x",
        "code": "4.x.x",
        "lab": "11.x.x"
    },
    "scripts": {
        "test": "node node_modules/lab/bin/lab -a code -t 100 -L",
        "test-cov-html": "node node_modules/lab/bin/lab -a code -r html -o coverage.html"
    },
    "license": "BSD-3-Clause"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
