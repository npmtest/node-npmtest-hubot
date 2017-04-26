# npmtest-hubot

#### basic test coverage for  [hubot (v2.19.0)](https://github.com/github/hubot#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-hubot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hubot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hubot.svg)](https://travis-ci.org/npmtest/node-npmtest-hubot)

#### A simple helpful robot for your Company

[![NPM](https://nodei.co/npm/hubot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hubot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hubot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hubot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hubot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hubot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hubot/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hubot/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hubot/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hubot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hubot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hubot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hubot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hubot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hubot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hubot/build/test-report.html](https://npmtest.github.io/node-npmtest-hubot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hubot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hubot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hubot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hubot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hubot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hubot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hubot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hubot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hubot"
    },
    "bin": {
        "hubot": "./bin/hubot"
    },
    "bugs": {
        "url": "https://github.com/github/hubot/issues"
    },
    "dependencies": {
        "async": ">=0.1.0 <1.0.0",
        "chalk": "^1.0.0",
        "cline": "^0.8.2",
        "coffee-script": "1.6.3",
        "connect-multiparty": "^1.2.5",
        "express": "^3.21.2",
        "log": "1.4.0",
        "optparse": "1.0.4",
        "scoped-http-client": "0.11.0"
    },
    "description": "A simple helpful robot for your Company",
    "devDependencies": {
        "chai": "~2.1.0",
        "coffee-errors": "0.8.6",
        "hubot-mock-adapter": "^1.0.0",
        "mocha": "^2.1.0",
        "mockery": "^1.4.0",
        "sinon": "~1.17.0",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "87c572d210fb0d5f89f756177ae0020d49ffba36",
        "tarball": "https://registry.npmjs.org/hubot/-/hubot-2.19.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.x",
        "npm": ">= 1.1.x"
    },
    "gitHead": "c0f6bdf947c5271c2cac5d48730320b129c2e44f",
    "homepage": "https://github.com/github/hubot#readme",
    "keywords": [
        "github",
        "hubot",
        "campfire",
        "bot"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "technicalpickles"
        },
        {
            "name": "bhuga"
        },
        {
            "name": "bkeepers"
        },
        {
            "name": "michaelansel"
        }
    ],
    "name": "hubot",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/github/hubot.git"
    },
    "scripts": {
        "test": "./script/test"
    },
    "version": "2.19.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
