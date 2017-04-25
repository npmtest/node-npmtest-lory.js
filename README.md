# npmtest-lory.js

#### basic test coverage for  [lory.js (v2.2.1)](https://github.com/meandmax/lory#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lory.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lory.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lory.js.svg)](https://travis-ci.org/npmtest/node-npmtest-lory.js)

#### Touch enabled minimalistic slider written in vanilla JavaScript.

[![NPM](https://nodei.co/npm/lory.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lory.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lory.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lory.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lory.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lory.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lory.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-lory.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-lory.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lory.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lory.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lory.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lory.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lory.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lory.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lory.js/build/test-report.html](https://npmtest.github.io/node-npmtest-lory.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lory.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lory.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lory.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lory.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lory.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lory.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lory.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lory.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maximilian Heinz",
        "url": "https://twitter.com/_meandmax_"
    },
    "betterScripts": {
        "compile": {
            "command": "babel-node bin/compile",
            "env": {
                "DEBUG": "app:*"
            }
        },
        "start": {
            "command": "babel-node bin/server",
            "env": {
                "DEBUG": "app:*"
            }
        },
        "dev": {
            "command": "nodemon --exec babel-node bin/server",
            "env": {
                "NODE_ENV": "development",
                "DEBUG": "app:*"
            }
        },
        "build": {
            "command": "npm run clean && better-npm-run compile",
            "env": {
                "NODE_ENV": "production",
                "DEBUG": "app:*"
            }
        }
    },
    "bugs": {
        "url": "https://github.com/meandmax/lory/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {},
    "description": "Touch enabled minimalistic slider written in vanilla JavaScript.",
    "devDependencies": {
        "babel-cli": "6.14.0",
        "babel-core": "6.14.0",
        "babel-loader": "6.2.5",
        "babel-preset-es2015": "6.14.0",
        "babel-preset-stage-0": "6.5.0",
        "babel-register": "6.14.0",
        "babel-runtime": "6.11.6",
        "better-npm-run": "0.0.11",
        "chai": "3.5.0",
        "clamp.js": "0.2.9",
        "custom-event": "1.0.0",
        "cz-conventional-changelog": "1.2.0",
        "debug": "2.2.0",
        "dependency-check": "2.6.0",
        "eslint": "3.5.0",
        "eslint-config-standard": "6.0.1",
        "eslint-plugin-promise": "2.0.1",
        "eslint-plugin-standard": "2.0.0",
        "extract-text-webpack-plugin": "1.0.1",
        "file-loader": "0.9.0",
        "fs-extra": "0.30.0",
        "html-loader": "0.4.4",
        "html-webpack-plugin": "2.22.0",
        "karma": "1.3.0",
        "karma-chai": "0.1.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-firefox-launcher": "1.0.0",
        "karma-fixture": "0.2.6",
        "karma-html2js-preprocessor": "1.0.0",
        "karma-ie-launcher": "1.0.0",
        "karma-mocha": "1.1.1",
        "karma-mocha-reporter": "2.1.0",
        "karma-opera-launcher": "1.0.0",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-safari-launcher": "1.0.0",
        "karma-sauce-launcher": "1.0.0",
        "mocha": "3.0.2",
        "nodemon": "1.10.2",
        "phantomjs-prebuilt": "2.1.12",
        "rimraf": "2.5.4",
        "sauce-connect-launcher": "0.16.0",
        "saucelabs": "1.3.0",
        "semantic-release": "4.3.5",
        "uglify-js": "2.7.3",
        "unminified-webpack-plugin": "1.1.0",
        "url-loader": "0.5.7",
        "webpack": "1.13.2",
        "webpack-dev-server": "1.16.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e45ff82f1e403ee9df5e9c01b31636a09f45a743",
        "tarball": "https://registry.npmjs.org/lory.js/-/lory.js-2.2.1.tgz"
    },
    "engines": {
        "node": ">= 5.2.0"
    },
    "gitHead": "3d71658eddc1cf3af1d9b3ba9b44c43f216a5797",
    "homepage": "https://github.com/meandmax/lory#readme",
    "inceptionYear": 2015,
    "jsnext:main": "./src/lory.js",
    "keywords": [
        "responsive",
        "lightweight",
        "minimalistic",
        "carousel",
        "slider",
        "touch",
        "slideshow",
        "jQuery",
        "mobile"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.githubusercontent.com/meandmax/lory/master/LICENSE"
        }
    ],
    "main": "./dist/lory.js",
    "maintainers": [
        {
            "name": "meandmax"
        }
    ],
    "name": "lory.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/meandmax/lory.git"
    },
    "scripts": {
        "build": "better-npm-run build",
        "check": "npm run lint -s && dependency-check package.json",
        "clean": "rimraf dist/*",
        "dev": "better-npm-run dev",
        "karma-local": "karma start local.karma.conf.js",
        "karma-sauce": "karma start saucelabs.karma.conf.js",
        "karma-travis": "karma start travis.karma.conf.js",
        "lint": "eslint src",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "start": "better-npm-run start",
        "travis": "npm run build && npm run karma-travis"
    },
    "version": "2.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
