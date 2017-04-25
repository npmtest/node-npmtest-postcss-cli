# npmtest-postcss-cli

#### basic test coverage for  [postcss-cli (v3.2.0)](https://github.com/postcss/postcss-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-cli)

#### CLI for PostCSS

[![NPM](https://nodei.co/npm/postcss-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-postcss-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-postcss-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        {
            "name": "Michael Ciniawky"
        },
        {
            "name": "Ryan Zimmermann"
        }
    ],
    "bin": {
        "postcss": "./bin/postcss"
    },
    "bugs": {
        "url": "https://github.com/postcss/postcss-cli/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "chokidar": "^1.6.1",
        "dependency-graph": "^0.5.0",
        "fs-promise": "^2.0.2",
        "get-stdin": "^5.0.1",
        "globby": "^6.1.0",
        "ora": "^1.1.0",
        "postcss": "^5.2.16",
        "postcss-load-config": "^1.1.0",
        "postcss-reporter": "^3.0.0",
        "read-cache": "^1.0.0",
        "yargs": "^7.0.2"
    },
    "description": "CLI for PostCSS",
    "devDependencies": {
        "ava": "^0.18.2",
        "coveralls": "^2.12.0",
        "nyc": "^10.1.2",
        "postcss-import": "^9.1.0",
        "standard": "^9.0.1",
        "sugarss": "^0.2.0",
        "uuid": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6128d913e250d07f41834cc76f714882cfa247ab",
        "tarball": "https://registry.npmjs.org/postcss-cli/-/postcss-cli-3.2.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "bin",
        "index.js",
        "lib"
    ],
    "gitHead": "1dac9bc5dd75488197fde1a83909a907e20cf588",
    "homepage": "https://github.com/postcss/postcss-cli#readme",
    "keywords": [
        "cli",
        "postcss",
        "postcss-runner"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ai"
        },
        {
            "name": "pirxpilot"
        },
        {
            "name": "ryanzim"
        },
        {
            "name": "watilde"
        }
    ],
    "name": "postcss-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/postcss/postcss-cli.git"
    },
    "scripts": {
        "clean": "node test/helpers/clean.js",
        "lint": "standard",
        "pretest": "npm run clean && npm run lint",
        "test": "nyc ava -v"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
