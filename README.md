# test coverage for  [spoof (v1.2.0)](http://feross.org/spoofmac/)  [![npm package](https://img.shields.io/npm/v/npmtest-spoof.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spoof) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spoof.svg)](https://travis-ci.org/npmtest/node-npmtest-spoof)
#### Easily spoof your MAC address in OS X & Linux

[![NPM](https://nodei.co/npm/spoof.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spoof)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spoof/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spoof/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spoof/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spoof/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spoof/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spoof/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spoof/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-spoof/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-spoof/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spoof/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-spoof/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-spoof/build/test-report.html](https://npmtest.github.io/node-npmtest-spoof/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-spoof/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spoof/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-spoof/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spoof/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spoof/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spoof/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spoof/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spoof/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bin": {
        "spoof": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/feross/spoof/issues"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "minimist": "^1.1.0",
        "shell-quote": "^1.4.1",
        "winreg": "^1.1.1",
        "zero-fill": "^2.1.0"
    },
    "description": "Easily spoof your MAC address in OS X & Linux",
    "devDependencies": {
        "standard": "*",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7b8b954df47b80798387994718dee14e590db58e",
        "tarball": "https://registry.npmjs.org/spoof/-/spoof-1.2.0.tgz"
    },
    "gitHead": "cf5341f87aafad2dac6b9ede8fb343cf941ec12e",
    "homepage": "http://feross.org/spoofmac/",
    "keywords": [
        "spoof",
        "MAC address",
        "mac",
        "spoofmac",
        "spoof mac address",
        "macchanger",
        "change",
        "modify",
        "set mac",
        "address",
        "mad science"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "spoof",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/spoof.git"
    },
    "scripts": {
        "test": "standard && tape test/*.js"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
