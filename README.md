# npmtest-react-tooltip

#### basic test coverage for  [react-tooltip (v3.3.0)](https://github.com/wwayne/react-tooltip)  [![npm package](https://img.shields.io/npm/v/npmtest-react-tooltip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-tooltip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-tooltip.svg)](https://travis-ci.org/npmtest/node-npmtest-react-tooltip)

#### react tooltip component

[![NPM](https://nodei.co/npm/react-tooltip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-tooltip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-tooltip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tooltip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-tooltip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-tooltip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-tooltip/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-tooltip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-tooltip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-tooltip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-tooltip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tooltip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-tooltip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-tooltip/build/test-report.html](https://npmtest.github.io/node-npmtest-react-tooltip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-tooltip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-tooltip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-tooltip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-tooltip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-tooltip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-tooltip",
    "version": "3.3.0",
    "description": "react tooltip component",
    "main": "dist/index.js",
    "scripts": {
        "test": "make test",
        "start": "make dev",
        "deploy": "make deploy"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "dist/",
            "standalone/",
            "src/style.js",
            "src/style.css",
            "example/"
        ]
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/wwayne/react-tooltip"
    },
    "keywords": [
        "react",
        "react-component",
        "tooltip",
        "react-tooltip"
    ],
    "author": "wwayne",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/wwayne/react-tooltip/issues"
    },
    "homepage": "https://github.com/wwayne/react-tooltip",
    "browserify-shim": {
        "react": "global:React",
        "react-dom": "global:ReactDOM"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "dependencies": {
        "classnames": "^2.2.0",
        "prop-types": "^15.5.8"
    },
    "engines": {
        "node": ">=4.2.1"
    },
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-core": "^6.9.1",
        "babel-eslint": "^4.1.1",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-plugin-transform-runtime": "^6.5.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "babelify": "^7.2.0",
        "browserify": "^13.0.0",
        "browserify-shim": "^3.8.12",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.5.0",
        "concurrently": "^2.1.0",
        "enzyme": "^2.3.0",
        "http-server": "^0.8.0",
        "jsdom": "^9.2.1",
        "mocha": "^2.5.3",
        "node-sass": "^3.7.0",
        "react-addons-test-utils": "^15.1.0",
        "sinon": "^1.17.4",
        "snazzy": "^2.0.1",
        "standard": "^5.2.2",
        "uglifyjs": "^2.4.10",
        "watchify": "^3.2.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
