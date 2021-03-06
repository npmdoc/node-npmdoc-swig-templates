# npmdoc-swig-templates

#### basic api documentation for  [swig-templates (v2.0.2)](https://github.com/node-swig/swig-templates#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-swig-templates.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-swig-templates) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-swig-templates.svg)](https://travis-ci.org/npmdoc/node-npmdoc-swig-templates)

#### A simple, powerful, and extendable templating engine for node.js and browsers, similar to Django, Jinja2, and Twig.

[![NPM](https://nodei.co/npm/swig-templates.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swig-templates)

- [https://npmdoc.github.io/node-npmdoc-swig-templates/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swig-templates/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swig-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swig-templates/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-swig-templates/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-swig-templates/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "swig": "./bin/swig.js"
    },
    "bugs": {
        "url": "https://github.com/node-swig/swig-templates/issues"
    },
    "config": {
        "blanket": {
            "pattern": "swig-templates/lib"
        },
        "travis-cov": {
            "threshold": 95
        }
    },
    "dependencies": {
        "optimist": "~0.6",
        "uglify-js": "2.6.0"
    },
    "description": "A simple, powerful, and extendable templating engine for node.js and browsers, similar to Django, Jinja2, and Twig.",
    "devDependencies": {
        "blanket": "~1.1",
        "browserify": "~2",
        "eslint": "^2.2.0",
        "expect.js": "~0.2",
        "express": "~3",
        "file": "~0.2",
        "git-validate": "^2.1.4",
        "jsdoc": "3.2.0",
        "less": "~1.4",
        "lodash": "~1.3.1",
        "mocha": "1.12.0",
        "mocha-phantomjs": "~3.1",
        "phantomjs": "~1.9.1",
        "rimraf": "^2.5.2",
        "still": "0.0.7",
        "travis-cov": "~0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d2502a7303019356f4ea76ea9065d4f58af6ab75",
        "tarball": "https://registry.npmjs.org/swig-templates/-/swig-templates-2.0.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "7a0b2ee4adac5faff774b439e3729c4e74ae8a94",
    "homepage": "https://github.com/node-swig/swig-templates#readme",
    "keywords": [
        "template",
        "templating",
        "html",
        "django",
        "jinja",
        "twig",
        "express",
        "block"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "cdaringe"
        },
        {
            "name": "lochlan"
        },
        {
            "name": "paulcpederson"
        }
    ],
    "name": "swig-templates",
    "optionalDependencies": {},
    "pre-commit": [
        "validate",
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/node-swig/swig-templates.git"
    },
    "scripts": {
        "lint": "make lint",
        "prepublish": "npm prune && make build",
        "test": "make test reporter=spec && make test-browser && make coverage cov-reporter=travis-cov",
        "validate": "npm ls"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
