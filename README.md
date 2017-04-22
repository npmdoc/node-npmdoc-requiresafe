# npmdoc-requiresafe

#### api documentation for  [requiresafe (v2.3.1)](https://github.com/requiresafe/cli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-requiresafe.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-requiresafe) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-requiresafe.svg)](https://travis-ci.org/npmdoc/node-npmdoc-requiresafe)

#### the requiresafe.com command line interface tool

[![NPM](https://nodei.co/npm/requiresafe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/requiresafe)

- [https://npmdoc.github.io/node-npmdoc-requiresafe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-requiresafe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-requiresafe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-requiresafe/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-requiresafe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-requiresafe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "^lift security"
    },
    "bin": {
        "requiresafe": "bin/requiresafe"
    },
    "bugs": {
        "url": "https://github.com/requiresafe/cli/issues"
    },
    "dependencies": {
        "chalk": "^1.1.1",
        "cli-table": "^0.3.1",
        "https-proxy-agent": "^1.0.0",
        "joi": "^6.9.1",
        "rc": "^1.1.2",
        "requiresafe-npm-utils": "^2.5.3",
        "semver": "^5.0.3",
        "subcommand": "^2.0.3",
        "wreck": "^6.3.0"
    },
    "deprecated": "please update to use nsp@2.0.0 or greater",
    "description": "the requiresafe.com command line interface tool",
    "devDependencies": {
        "code": "^1.5.0",
        "eslint-config-requiresafe": "^1.0.0",
        "git-validate": "^2.1.0",
        "lab": "^6.1.0",
        "nock": "^2.15.0",
        "shrinkydink": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b295e64ded1f39349e484c6b6f18ff663544d953",
        "tarball": "https://registry.npmjs.org/requiresafe/-/requiresafe-2.3.1.tgz"
    },
    "gitHead": "80b86a7c4d98173509aa4cc21334b98f0d170682",
    "homepage": "https://github.com/requiresafe/cli#readme",
    "keywords": [
        "security",
        "requiresafe"
    ],
    "license": "Apache-2.0",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "adam_baldwin"
        },
        {
            "name": "latentflip"
        },
        {
            "name": "nlf"
        }
    ],
    "name": "requiresafe",
    "optionalDependencies": {},
    "pre-commit": [
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/requiresafe/cli.git"
    },
    "scripts": {
        "requiresafe": "bin/requiresafe check",
        "setup-offline": "curl -sS https://api.requiresafe.com/advisories -o advisories.json",
        "shrinkwrap": "npm shrinkwrap && shrinkydink",
        "test": "lab -a code -L -t 100"
    },
    "version": "2.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
