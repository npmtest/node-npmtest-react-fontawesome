# npmtest-react-fontawesome

#### basic test coverage for  [react-fontawesome (v1.6.1)](https://github.com/danawoodman/react-fontawesome#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-fontawesome.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-fontawesome) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-fontawesome.svg)](https://travis-ci.org/npmtest/node-npmtest-react-fontawesome)

#### A React component for the font-awesome icon library.

[![NPM](https://nodei.co/npm/react-fontawesome.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-fontawesome)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-fontawesome/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-fontawesome/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-fontawesome/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-fontawesome/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-fontawesome/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-fontawesome/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-fontawesome/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-fontawesome/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-fontawesome/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-fontawesome/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-fontawesome/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-fontawesome/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-fontawesome/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-fontawesome/build/test-report.html](https://npmtest.github.io/node-npmtest-react-fontawesome/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-fontawesome/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-fontawesome/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-fontawesome/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-fontawesome/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dana Woodman",
        "url": "danawoodman.com"
    },
    "bugs": {
        "url": "https://github.com/danawoodman/react-fontawesome/issues"
    },
    "bujs": {
        "url": "https://github.com/danawoodman/react-fontawesome/issues"
    },
    "dependencies": {
        "prop-types": "^15.5.6"
    },
    "description": "A React component for the font-awesome icon library.",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.4",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "chai": "^3.2.0",
        "eslint": "^3.19.0",
        "eslint-plugin-nodeca": "^1.0.3",
        "eslint-plugin-react": "^6.10.3",
        "jsdoc-to-markdown": "^3.0.0",
        "jsdom": "^9.12.0",
        "mocha": "^3.2.0",
        "mocha-jsdom": "^1.0.0",
        "mocha-sinon": "^2.0.0",
        "prettier-eslint": "^5.1.0",
        "prettier-eslint-cli": "^3.4.1",
        "react": "^15.0.1",
        "react-dom": "^15.0.1",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "eddce17e7dc731aa09fd4a186688a61793a16c5c",
        "tarball": "https://registry.npmjs.org/react-fontawesome/-/react-fontawesome-1.6.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "40eca64bef0ae591a21dc1538659c07ff415525e",
    "homepage": "https://github.com/danawoodman/react-fontawesome#readme",
    "keywords": [
        "react",
        "font-awesome",
        "fontawesome",
        "bootstrap",
        "icons",
        "fonts",
        "icon",
        "danawoodman",
        "big",
        "style",
        "jsx",
        "react-component",
        "component"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "danawoodman"
        }
    ],
    "name": "react-fontawesome",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.12.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danawoodman/react-fontawesome.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "dist": "npm run format && npm run build && npm test && npm run docs",
        "docs": "jsdoc2md lib/index.js > api.md",
        "format": "prettier-eslint '{src,test}/**/*.js' --prettier.single-quote --prettier.no-semi es5 --write",
        "test": "mocha",
        "watch": "npm run watch-build & npm run watch-test",
        "watch-build": "npm run build -- --watch",
        "watch-test": "npm run test -- -w"
    },
    "version": "1.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
