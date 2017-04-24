# npmtest-fs-utils

#### basic test coverage for  [fs-utils (v0.7.0)](https://github.com/assemble/fs-utils)  [![npm package](https://img.shields.io/npm/v/npmtest-fs-utils.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fs-utils) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fs-utils.svg)](https://travis-ci.org/npmtest/node-npmtest-fs-utils)

#### fs extras and utilities to extend the node.js file system module. Used in Assemble and many other projects.

[![NPM](https://nodei.co/npm/fs-utils.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fs-utils)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fs-utils/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fs-utils/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fs-utils/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fs-utils/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fs-utils/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fs-utils/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fs-utils/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fs-utils/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fs-utils/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fs-utils/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fs-utils/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fs-utils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fs-utils/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fs-utils/build/test-report.html](https://npmtest.github.io/node-npmtest-fs-utils/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fs-utils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fs-utils/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fs-utils/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fs-utils/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fs-utils/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fs-utils/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fs-utils/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fs-utils/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/assemble"
    },
    "bugs": {
        "url": "https://github.com/assemble/fs-utils/issues"
    },
    "dependencies": {
        "async": "^1.5.0",
        "delete": "^0.2.1",
        "extend-shallow": "^2.0.1",
        "graceful-fs": "^4.1.2",
        "is-absolute": "^0.2.3",
        "js-yaml": "^3.4.3",
        "kind-of": "^3.0.0",
        "lazy-cache": "^0.2.4",
        "matched": "^0.3.2",
        "normalize-path": "^2.0.1",
        "read-data": "^0.3.0",
        "read-yaml": "^1.0.0",
        "relative": "^3.0.2",
        "write": "^0.2.1",
        "write-data": "^0.1.0",
        "write-json": "^0.2.2",
        "write-yaml": "^0.2.2"
    },
    "description": "fs extras and utilities to extend the node.js file system module. Used in Assemble and many other projects.",
    "devDependencies": {
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "3bf359d0328649a7f1d93f041200035635d06087",
        "tarball": "https://registry.npmjs.org/fs-utils/-/fs-utils-0.7.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "index.js",
        "utils.js"
    ],
    "gitHead": "bea9667318c7ecb2d0c7cbb502ddcfa7dce59888",
    "homepage": "https://github.com/assemble/fs-utils",
    "keywords": [
        "file",
        "file system",
        "fs",
        "node",
        "node.js",
        "path",
        "read",
        "readFile",
        "readFileSync",
        "utils"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        },
        {
            "name": "doowb"
        }
    ],
    "name": "fs-utils",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/assemble/fs-utils.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "related": {
            "list": [
                "write-data",
                "write-json",
                "read-data",
                "read-yaml",
                "write-yaml"
            ]
        }
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
