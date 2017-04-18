# npmdoc-jsesc

#### api documentation for  [jsesc (v2.5.0)](https://mths.be/jsesc)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsesc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsesc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsesc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsesc)

#### Given some data, jsesc returns the shortest possible stringified & ASCII-safe representation of that data.

[![NPM](https://nodei.co/npm/jsesc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsesc)

- [https://npmdoc.github.io/node-npmdoc-jsesc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsesc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsesc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsesc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsesc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsesc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Bynens",
        "url": "https://mathiasbynens.be/"
    },
    "bin": {
        "jsesc": "bin/jsesc"
    },
    "bugs": {
        "url": "https://github.com/mathiasbynens/jsesc/issues"
    },
    "dependencies": {},
    "description": "Given some data, jsesc returns the shortest possible stringified & ASCII-safe representation of that data.",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "grunt": "^0.4.5",
        "grunt-template": "^0.2.3",
        "istanbul": "^0.4.2",
        "mocha": "*",
        "regenerate": "^1.3.0",
        "requirejs": "^2.1.22"
    },
    "directories": {},
    "dist": {
        "shasum": "ce895de28feb034dcbf55fbeeabbcaeb63d73086",
        "tarball": "https://registry.npmjs.org/jsesc/-/jsesc-2.5.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "LICENSE-MIT.txt",
        "jsesc.js",
        "bin/",
        "man/"
    ],
    "gitHead": "079324382d7cb7aa90e0ec45fb636b22fc45e1c1",
    "homepage": "https://mths.be/jsesc",
    "keywords": [
        "buffer",
        "escape",
        "javascript",
        "json",
        "map",
        "set",
        "string",
        "stringify",
        "tool"
    ],
    "license": "MIT",
    "main": "jsesc.js",
    "maintainers": [
        {
            "name": "mathias"
        }
    ],
    "man": [
        "man/jsesc.1"
    ],
    "name": "jsesc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mathiasbynens/jsesc.git"
    },
    "scripts": {
        "build": "grunt template",
        "cover": "istanbul cover --report 'html' --verbose --dir 'coverage' 'tests/tests.js'",
        "coveralls": "istanbul cover --verbose --dir 'coverage' 'tests/tests.js' && coveralls < coverage/lcov.info'",
        "test": "mocha tests"
    },
    "version": "2.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
