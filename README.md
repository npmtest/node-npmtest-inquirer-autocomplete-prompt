# npmtest-inquirer-autocomplete-prompt

#### basic test coverage for  [inquirer-autocomplete-prompt (v0.8.0)](https://github.com/mokkabonna/inquirer-autocomplete-prompt#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-inquirer-autocomplete-prompt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-inquirer-autocomplete-prompt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-inquirer-autocomplete-prompt.svg)](https://travis-ci.org/npmtest/node-npmtest-inquirer-autocomplete-prompt)

#### Autocomplete prompt for inquirer

[![NPM](https://nodei.co/npm/inquirer-autocomplete-prompt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inquirer-autocomplete-prompt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-inquirer-autocomplete-prompt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-inquirer-autocomplete-prompt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/test-report.html](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inquirer-autocomplete-prompt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-inquirer-autocomplete-prompt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Martin Hansen"
    },
    "bugs": {
        "url": "https://github.com/mokkabonna/inquirer-autocomplete-prompt/issues"
    },
    "dependencies": {
        "ansi-escapes": "^1.1.0",
        "chalk": "^1.1.3",
        "figures": "^2.0.0",
        "inquirer": "3.0.5",
        "lodash": "^4.17.4",
        "util": "^0.10.3"
    },
    "description": "Autocomplete prompt for inquirer",
    "devDependencies": {
        "bluebird": "^3.0.5",
        "chai": "^3.4.1",
        "fuzzy": "^0.1.3",
        "istanbul": "^0.3.8",
        "jscs": "^1.6.1",
        "jshint": "^2.5.6",
        "lodash": "^3.10.1",
        "mocha": "^2.2.1",
        "promise": "^7.0.4",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "cf17dcef93f031932ee90d6e8ccc62a806d7ba7a",
        "tarball": "https://registry.npmjs.org/inquirer-autocomplete-prompt/-/inquirer-autocomplete-prompt-0.8.0.tgz"
    },
    "gitHead": "c58d4a250b6caa46849e9b1064680587a94abf72",
    "homepage": "https://github.com/mokkabonna/inquirer-autocomplete-prompt#readme",
    "license": "ISC",
    "maintainers": [
        {
            "name": "mokkabonna"
        }
    ],
    "name": "inquirer-autocomplete-prompt",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "http://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mokkabonna/inquirer-autocomplete-prompt.git"
    },
    "scripts": {
        "checkStyle": "jscs .",
        "lint": "jshint .",
        "posttest": "istanbul check-coverage --statements 85 --branches 85 --functions 85 --lines 85 && rm -rf coverage",
        "pretest": "npm run-script lint && npm run-script checkStyle",
        "test": "istanbul cover ./node_modules/.bin/_mocha test/spec"
    },
    "version": "0.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
