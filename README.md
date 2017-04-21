# npmtest-base

#### basic test coverage for  [base (v0.13.0)](https://github.com/node-base/base)  [![npm package](https://img.shields.io/npm/v/npmtest-base.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-base) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-base.svg)](https://travis-ci.org/npmtest/node-npmtest-base)

#### Framework for rapidly creating high quality node.js applications, using plugins like building blocks

[![NPM](https://nodei.co/npm/base.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/base)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-base/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-base/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-base/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-base/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-base/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-base/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-base/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-base/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-base/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-base/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-base/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-base/build/test-report.html](https://npmtest.github.io/node-npmtest-base/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-base/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-base/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-base/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-base/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-base/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-base/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-base/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-base/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "base",
    "description": "Framework for rapidly creating high quality node.js applications, using plugins like building blocks",
    "version": "0.13.0",
    "homepage": "https://github.com/node-base/base",
    "author": "Jon Schlinkert (https://github.com/jonschlinkert)",
    "maintainers": [
        "Brian Woodward (https://github.com/doowb)",
        "Jon Schlinkert (https://github.com/jonschlinkert)"
    ],
    "contributors": [
        "<wtgtybhertgeghgtwtg@gmail.com> (https://github.com/wtgtybhertgeghgtwtg)",
        "Brian Woodward <brian.woodward@gmail.com> (https://twitter.com/doowb)",
        "Charlike Mike Reagent (https://i.am.charlike.online)",
        "John O'Donnell (https://github.com/criticalmash)",
        "Jon Schlinkert <jon.schlinkert@sellside.com> (http://twitter.com/jonschlinkert)"
    ],
    "repository": "node-base/base",
    "bugs": {
        "url": "https://github.com/node-base/base/issues"
    },
    "license": "MIT",
    "files": [
        "index.js"
    ],
    "main": "index.js",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "dependencies": {
        "arr-union": "^3.1.0",
        "cache-base": "^1.0.0",
        "class-utils": "^0.3.5",
        "component-emitter": "^1.2.1",
        "define-property": "^0.2.5",
        "isobject": "^3.0.0",
        "mixin-deep": "^1.2.0",
        "pascalcase": "^0.1.1"
    },
    "devDependencies": {
        "gulp-format-md": "^0.1.11",
        "helper-changelog": "^0.3.0",
        "mocha": "^3.2.0",
        "through2": "^2.0.3",
        "verb-generate-readme": "^0.4.3"
    },
    "keywords": [
        "base",
        "boilerplate",
        "cache",
        "del",
        "get",
        "inherit",
        "methods",
        "set",
        "starter",
        "unset",
        "visit"
    ],
    "verb": {
        "run": true,
        "toc": false,
        "layout": null,
        "tasks": [
            "readme"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "helpers": [
            "helper-changelog"
        ],
        "related": {
            "description": "There are a number of different plugins available for extending base. Let us know if you create your own!",
            "hightlight": "generate",
            "list": [
                "base-cwd",
                "base-data",
                "base-fs",
                "base-generators",
                "base-option",
                "base-pipeline",
                "base-pkg",
                "base-plugins",
                "base-questions",
                "base-store",
                "base-task"
            ]
        },
        "reflinks": [
            "assemble",
            "base",
            "base-plugins",
            "cache-base",
            "class-utils",
            "enquirer",
            "generate",
            "helper-changelog",
            "prompt-base",
            "static-extend",
            "templates",
            "update",
            "verb"
        ],
        "lint": {
            "reflinks": true
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
