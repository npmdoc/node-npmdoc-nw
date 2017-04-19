# npmdoc-nw

#### api documentation for  [nw (v0.21.6)](https://github.com/nwjs/npm-installer#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nw.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nw) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nw.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nw)

#### A installer for nw.js

[![NPM](https://nodei.co/npm/nw.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nw)

- [https://npmdoc.github.io/node-npmdoc-nw/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nw/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nw/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nw/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nw/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nw/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young"
    },
    "bin": {
        "nw": "bin/nw"
    },
    "bugs": {
        "url": "https://github.com/nwjs/npm-installer/issues"
    },
    "dependencies": {
        "chalk": "~1.1.3",
        "decompress": "^3.0.0",
        "download": "^4.4.3",
        "file-exists": "^2.0.0",
        "merge": "^1.2.0",
        "multimeter": "^0.1.1",
        "rimraf": "^2.2.8",
        "semver": "^5.1.0",
        "yargs": "^3.2.1"
    },
    "description": "A installer for nw.js",
    "devDependencies": {
        "request": "^2.53.0",
        "tape": "^3.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "22d7894551d665692222e7f3bef50586e6c87e90",
        "tarball": "https://registry.npmjs.org/nw/-/nw-0.21.6.tgz"
    },
    "files": [
        "lib",
        "bin",
        "scripts",
        "index.js"
    ],
    "gitHead": "76f414cc4c0fbcbb7dca4d53084307de82e7d91a",
    "homepage": "https://github.com/nwjs/npm-installer#readme",
    "keywords": [
        "nw",
        "nw.js",
        "nwjs",
        "chromium",
        "io.js",
        "node-webkit",
        "webkit",
        "installer",
        "desktop",
        "application"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mithgol"
        },
        {
            "name": "rogerwang"
        },
        {
            "name": "shama"
        }
    ],
    "name": "nw",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nwjs/npm-installer.git"
    },
    "scripts": {
        "postinstall": "node scripts/install.js",
        "test": "node test/index.js"
    },
    "version": "0.21.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
