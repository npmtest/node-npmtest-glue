# npmtest-glue

#### basic test coverage for  [glue (v4.1.0)](https://github.com/hapijs/glue#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-glue.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-glue) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-glue.svg)](https://travis-ci.org/npmtest/node-npmtest-glue)

#### Server composer for hapi.js

[![NPM](https://nodei.co/npm/glue.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glue)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-glue/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-glue/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-glue/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-glue/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-glue/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-glue/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-glue/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-glue/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-glue/tree/gh-pages/build)|

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
    "bugs": {
        "url": "https://github.com/hapijs/glue/issues"
    },
    "dependencies": {
        "hapi": "11.x.x || 12.x.x || 13.x.x || 14.x.x || 15.x.x || 16.x.x",
        "hoek": "4.x.x",
        "items": "2.x.x",
        "joi": "10.x.x"
    },
    "description": "Server composer for hapi.js",
    "devDependencies": {
        "catbox-memory": "2.x.x",
        "code": "4.x.x",
        "lab": "11.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "07ab6438cca589a306b0bbc36347b821b697402f",
        "tarball": "https://registry.npmjs.org/glue/-/glue-4.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "8dc31113ee620dea13fc3b94c6cb9bcb3fa81ace",
    "homepage": "https://github.com/hapijs/glue#readme",
    "keywords": [
        "server",
        "pack",
        "composer",
        "manifest",
        "hapi"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "csrl"
        }
    ],
    "name": "glue",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/glue.git"
    },
    "scripts": {
        "test": "node node_modules/lab/bin/lab -a code -t 100 -L",
        "test-cov-html": "node node_modules/lab/bin/lab -a code -r html -o coverage.html"
    },
    "version": "4.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
