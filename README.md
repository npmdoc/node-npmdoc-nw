# api documentation for  [nw (v0.21.5)](https://github.com/nwjs/npm-installer#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nw.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nw) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nw.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nw)
#### A installer for nw.js

[![NPM](https://nodei.co/npm/nw.png?downloads=true)](https://www.npmjs.com/package/nw)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nw/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-nw_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nw/build/apidoc.html)

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
        "shasum": "7d502dc16f6035ce27e98921d3e41c88a5e620a7",
        "tarball": "https://registry.npmjs.org/nw/-/nw-0.21.5.tgz"
    },
    "files": [
        "lib",
        "bin",
        "scripts",
        "index.js"
    ],
    "gitHead": "a7201b6422ead2e3c9f5f0c04e9d1284d00a824d",
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
            "name": "mithgol",
            "email": "getgit@mithgol.ru"
        },
        {
            "name": "rogerwang",
            "email": "wenrui@gmail.com"
        },
        {
            "name": "shama",
            "email": "kyle@dontkry.com"
        }
    ],
    "name": "nw",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nwjs/npm-installer.git"
    },
    "scripts": {
        "postinstall": "node scripts/install.js",
        "test": "node test/index.js"
    },
    "version": "0.21.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module nw](#apidoc.module.nw)
1.  [function <span class="apidocSignatureSpan">nw.</span>findpath ()](#apidoc.element.nw.findpath)



# <a name="apidoc.module.nw"></a>[module nw](#apidoc.module.nw)

#### <a name="apidoc.element.nw.findpath"></a>[function <span class="apidocSignatureSpan">nw.</span>findpath ()](#apidoc.element.nw.findpath)
- description and source-code
```javascript
findpath = function () {
  var bin = bindir;
  if (process.platform === 'darwin') {
    if (fs.existsSync(path.join(bin, 'Contents'))) {
      bin = path.join(bin, 'Contents', 'MacOS', 'nwjs');
    } else {
      bin = path.join(bin, 'nwjs.app', 'Contents', 'MacOS', 'nwjs');
    }
  } else if (process.platform === 'win32') {
    bin = path.join(bin, 'nw.exe');
  } else {
    bin = path.join(bin, 'nw');
  }
  return bin;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
