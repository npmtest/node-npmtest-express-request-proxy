# npmtest-express-request-proxy

#### basic test coverage for  [express-request-proxy (v2.0.0)](https://github.com/4front/express-request-proxy)  [![npm package](https://img.shields.io/npm/v/npmtest-express-request-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-request-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-request-proxy.svg)](https://travis-ci.org/npmtest/node-npmtest-express-request-proxy)

#### Intelligent http proxy Express middleware

[![NPM](https://nodei.co/npm/express-request-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-request-proxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-request-proxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-request-proxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-request-proxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-request-proxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-request-proxy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-request-proxy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-request-proxy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-request-proxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-request-proxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-request-proxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-request-proxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-request-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-request-proxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-request-proxy/build/test-report.html](https://npmtest.github.io/node-npmtest-express-request-proxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-request-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-request-proxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-request-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-request-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-request-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-request-proxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-request-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-request-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Von Lehman",
        "url": "https://github.com/dvonlehman"
    },
    "bugs": {
        "url": "https://github.com/4front/express-request-proxy/issues"
    },
    "dependencies": {
        "async": "^1.4.0",
        "body-parser": "^1.12.0",
        "camel-case": "^1.1.1",
        "debug": "^2.1.1",
        "lodash": "^4.6.1",
        "lru-cache": "^4.0.0",
        "path-to-regexp": "^1.1.1",
        "request": "^2.53.0",
        "simple-errors": "^1.0.0",
        "through2": "^2.0.0",
        "type-is": "^1.6.6",
        "url-join": "0.0.1"
    },
    "description": "Intelligent http proxy Express middleware",
    "devDependencies": {
        "compression": "^1.6.0",
        "dash-assert": "^1.0.2",
        "eslint": "^2.3.0",
        "eslint-config-4front": "^1.1.3",
        "express": "^4.11.1",
        "istanbul": "^0.4.2",
        "memory-cache-stream": "^1.0.4",
        "mocha": "^2.4.5",
        "shortid": "^2.1.3",
        "sinon": "^1.15.4",
        "supertest": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "01919aec61e89a0f824fa5e6e733b8e063c9d64d",
        "tarball": "https://registry.npmjs.org/express-request-proxy/-/express-request-proxy-2.0.0.tgz"
    },
    "gitHead": "f4b0750a46c2659d38d852bf5f04f5961143096f",
    "homepage": "https://github.com/4front/express-request-proxy",
    "keywords": [
        "4front",
        "express",
        "middleware",
        "request",
        "api",
        "proxy"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dvonlehman"
        }
    ],
    "name": "express-request-proxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/4front/express-request-proxy.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
