# npmtest-pegjs

#### test coverage for  [pegjs (v0.10.0)](http://pegjs.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-pegjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pegjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pegjs.svg)](https://travis-ci.org/npmtest/node-npmtest-pegjs)

#### Parser generator for JavaScript

[![NPM](https://nodei.co/npm/pegjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pegjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pegjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pegjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pegjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pegjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pegjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pegjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pegjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pegjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pegjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pegjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pegjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pegjs/build/test-report.html](https://npmtest.github.io/node-npmtest-pegjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pegjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pegjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pegjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pegjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pegjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pegjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pegjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pegjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Majda",
        "url": "http://majda.cz/"
    },
    "bin": {
        "pegjs": "bin/pegjs"
    },
    "bugs": {
        "url": "https://github.com/pegjs/pegjs/issues"
    },
    "dependencies": {},
    "description": "Parser generator for JavaScript",
    "devDependencies": {
        "browserify": "13.1.0",
        "eslint": "2.13.1",
        "http-server": "0.9.0",
        "jasmine-node": "1.14.5",
        "uglify-js": "2.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cf8bafae6eddff4b5a7efb185269eaaf4610ddbd",
        "tarball": "https://registry.npmjs.org/pegjs/-/pegjs-0.10.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "CHANGELOG.md",
        "LICENSE",
        "README.md",
        "VERSION",
        "bin/pegjs",
        "examples/arithmetics.pegjs",
        "examples/css.pegjs",
        "examples/javascript.pegjs",
        "examples/json.pegjs",
        "lib/compiler/asts.js",
        "lib/compiler/index.js",
        "lib/compiler/js.js",
        "lib/compiler/opcodes.js",
        "lib/compiler/passes/generate-bytecode.js",
        "lib/compiler/passes/generate-js.js",
        "lib/compiler/passes/remove-proxy-rules.js",
        "lib/compiler/passes/report-duplicate-labels.js",
        "lib/compiler/passes/report-duplicate-rules.js",
        "lib/compiler/passes/report-infinite-recursion.js",
        "lib/compiler/passes/report-infinite-repetition.js",
        "lib/compiler/passes/report-undefined-rules.js",
        "lib/compiler/visitor.js",
        "lib/grammar-error.js",
        "lib/parser.js",
        "lib/peg.js",
        "lib/utils/arrays.js",
        "lib/utils/classes.js",
        "lib/utils/objects.js",
        "package.json"
    ],
    "gitHead": "671166bbe82150042b71d5756405c0ee067df961",
    "homepage": "http://pegjs.org/",
    "keywords": [
        "parser generator",
        "PEG"
    ],
    "license": "MIT",
    "main": "lib/peg",
    "maintainers": [
        {
            "name": "dmajda"
        }
    ],
    "name": "pegjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pegjs/pegjs.git"
    },
    "scripts": {
        "test": "make lint && make spec"
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
