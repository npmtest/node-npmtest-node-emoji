# npmtest-node-emoji

#### test coverage for  [node-emoji (v1.5.1)](https://github.com/omnidan/node-emoji#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-emoji.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-emoji) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-emoji.svg)](https://travis-ci.org/npmtest/node-npmtest-node-emoji)

#### simple emoji support for node.js projects

[![NPM](https://nodei.co/npm/node-emoji.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-emoji)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-emoji/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-emoji/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-emoji/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-emoji/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-emoji/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-emoji/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-emoji/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-emoji/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-emoji/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-emoji/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-emoji/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-emoji/build/test-report.html](https://npmtest.github.io/node-npmtest-node-emoji/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-emoji/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-emoji/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-emoji/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-emoji/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-emoji/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-emoji/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-emoji/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-emoji/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Bugl"
    },
    "bugs": {
        "url": "https://github.com/omnidan/node-emoji/issues"
    },
    "dependencies": {
        "string.prototype.codepointat": "^0.2.0"
    },
    "description": "simple emoji support for node.js projects",
    "devDependencies": {
        "istanbul": "^0.4.5",
        "mocha": "^3.0.2",
        "should": "^11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fd918e412769bf8c448051238233840b2aff16a1",
        "tarball": "https://registry.npmjs.org/node-emoji/-/node-emoji-1.5.1.tgz"
    },
    "gitHead": "b0a43f72e84ce612d9d6b72cd564b8c1bbde173b",
    "homepage": "https://github.com/omnidan/node-emoji#readme",
    "keywords": [
        "emoji",
        "simple",
        "emoticons",
        "emoticon",
        "emojis",
        "smiley",
        "smileys",
        "smilies",
        "ideogram",
        "ideograms"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "omnidan"
        }
    ],
    "name": "node-emoji",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/omnidan/node-emoji.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha test",
        "emojiparse": "node lib/emojiparse.js",
        "prepublish": "npm run test",
        "test": "mocha --require should --bail --reporter spec test/*"
    },
    "version": "1.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
