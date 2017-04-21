# npmtest-eslint-plugin-jsdoc

#### basic test coverage for  eslint-plugin-jsdoc (v3.0.2)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-jsdoc.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-jsdoc)

#### JSDoc linting rules for ESLint.

[![NPM](https://nodei.co/npm/eslint-plugin-jsdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-jsdoc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-jsdoc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-jsdoc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-jsdoc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-jsdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gajus Kuizinas",
        "url": "http://gajus.com"
    },
    "dependencies": {
        "comment-parser": "^0.4.0",
        "lodash": "^4.5.1"
    },
    "description": "JSDoc linting rules for ESLint.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-flow-strip-types": "^6.18.0",
        "babel-preset-env": "^1.2.2",
        "babel-register": "^6.18.0",
        "chai": "^3.5.0",
        "eslint": "^3.10.2",
        "eslint-config-canonical": "^5.5.0",
        "gitdown": "^2.4.0",
        "globby": "^4.0.0",
        "mocha": "^2.5.3",
        "semantic-release": "^6.3.6"
    },
    "engines": {
        "node": ">=4"
    },
    "keywords": [
        "eslint",
        "plugin",
        "jsdoc"
    ],
    "license": "BSD-3-Clause",
    "main": "./dist/index.js",
    "name": "eslint-plugin-jsdoc",
    "peerDependencies": {
        "eslint": ">=0.8.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/gajus/eslint-plugin-jsdoc"
    },
    "scripts": {
        "add-assertions": "babel-node --presets es2015 ./bin/readme-assertions",
        "build": "NODE_ENV=production babel ./src --out-dir ./dist --copy-files --source-maps",
        "generate-readme": "gitdown ./.README/README.md --output-file ./README.md && npm run add-assertions",
        "lint": "eslint ./src ./test",
        "test": "mocha --compilers js:babel-register"
    },
    "version": "3.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
