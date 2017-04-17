# test coverage for  [activator (v3.0.1)](https://github.com/deitch/activator#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-activator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-activator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-activator.svg)](https://travis-ci.org/npmtest/node-npmtest-activator)
#### simple user activation and password reset for nodejs

[![NPM](https://nodei.co/npm/activator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/activator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-activator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-activator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-activator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-activator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-activator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-activator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-activator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-activator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-activator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-activator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-activator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-activator/build/test-report.html](https://npmtest.github.io/node-npmtest-activator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-activator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-activator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-activator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-activator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-activator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-activator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-activator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-activator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Avi Deitcher http://github.com/deitch"
    },
    "bugs": {
        "url": "https://github.com/deitch/activator/issues"
    },
    "contributors": [
        {
            "name": "Avi Deitcher",
            "url": "http://github.com/deitcher"
        },
        {
            "name": "Sharry Stowell",
            "url": "https://github.com/molinto"
        },
        {
            "name": "Bartol Karuza",
            "url": "https://github.com/bartolkaruza"
        },
        {
            "name": "Clif Gordon",
            "url": "https://github.com/ClifG"
        },
        {
            "name": "Simon Boulet",
            "url": "https://github.com/siboulet"
        },
        {
            "name": "Stuart Longland",
            "url": "https://github.com/sjlongland"
        }
    ],
    "dependencies": {
        "async": "0.2.x",
        "jsonwebtoken": "^5.7.0",
        "lodash": ">=4.0.0",
        "nodemailer": ">=1.3.4",
        "styliner": "^1.0.0"
    },
    "description": "simple user activation and password reset for nodejs",
    "devDependencies": {
        "body-parser": "^1.12.2",
        "express": "4.x",
        "mocha": "^2.4.5",
        "should": "7.x.x",
        "smtp-tester": "~0.5.1",
        "supertest": "0.x"
    },
    "directories": {},
    "dist": {
        "shasum": "d60341475b5590fb26476df65b714e4aa5fbaf13",
        "tarball": "https://registry.npmjs.org/activator/-/activator-3.0.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "c3a0578f32a07f1a306ec5c94964f0dc6f956f79",
    "homepage": "https://github.com/deitch/activator#readme",
    "keywords": [
        "express",
        "email",
        "sms",
        "activation",
        "nodejs",
        "node",
        "confirmation",
        "two-step"
    ],
    "license": "MIT",
    "main": "./lib/activator.js",
    "maintainers": [
        {
            "name": "deitch"
        }
    ],
    "name": "activator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/deitch/activator.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "url": "http://github.com/deitch/activator",
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
