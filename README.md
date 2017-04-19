# npmdoc-express-winston

#### api documentation for  [express-winston (v2.3.0)](https://github.com/bithavoc/express-winston#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-winston.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-winston) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-winston.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-winston)

#### express.js middleware for flatiron/winston

[![NPM](https://nodei.co/npm/express-winston.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-winston)

- [https://npmdoc.github.io/node-npmdoc-express-winston/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-winston/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-winston/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-winston/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-winston/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-winston/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "bithavoc",
        "url": "http://bithavoc.io"
    },
    "bugs": {
        "url": "http://github.com/bithavoc/express-winston/issues"
    },
    "config": {
        "travis-cov": {
            "threshold": 100
        },
        "blanket": {
            "pattern": [
                "index.js"
            ],
            "data-cover-never": [
                "node_modules",
                "test"
            ]
        }
    },
    "contributors": [
        {
            "name": "Lars Jacob",
            "url": "http://jaclar.net"
        },
        {
            "name": "Jonathan Lomas",
            "url": "http://floatinglomas.ca"
        },
        {
            "name": "Xavier Damman",
            "url": "http://xdamman.com"
        },
        {
            "name": "Quentin Rossetti"
        },
        {
            "name": "Robbie Trencheny",
            "url": "http://robbie.io"
        }
    ],
    "dependencies": {
        "chalk": "~0.4.0",
        "lodash": "~4.11.1"
    },
    "description": "express.js middleware for flatiron/winston",
    "devDependencies": {
        "blanket": "^1.2.2",
        "mocha": "^2.4.5",
        "node-mocks-http": "^1.5.1",
        "promise": "^7.1.1",
        "should": "^8.2.2",
        "travis-cov": "^0.2.5",
        "winston": ">=1.x"
    },
    "directories": {},
    "dist": {
        "shasum": "8dea98617f96a53cc9c073159d08b0dc38c5f231",
        "tarball": "https://registry.npmjs.org/express-winston/-/express-winston-2.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "69456f1112db2a2c73621679ef684ffd690704f2",
    "homepage": "https://github.com/bithavoc/express-winston#readme",
    "keywords": [
        "winston",
        "flatiron",
        "logging",
        "express",
        "log",
        "error",
        "handler",
        "middleware",
        "colors"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bithavoc"
        },
        {
            "name": "floatinglomas"
        },
        {
            "name": "rosston"
        }
    ],
    "name": "express-winston",
    "optionalDependencies": {},
    "peerDependencies": {
        "winston": ">=1.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bithavoc/express-winston.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-coverage": "mocha --require blanket --reporter html-cov > coverage.html || true",
        "test-travis": "mocha --require blanket --reporter travis-cov"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
