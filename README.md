# npmdoc-pngquant

#### api documentation for  pngquant (v1.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-pngquant.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pngquant) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pngquant.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pngquant)

#### The pngquant utility as a readable/writable stream

[![NPM](https://nodei.co/npm/pngquant.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pngquant)

- [https://npmdoc.github.io/node-npmdoc-pngquant/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pngquant/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pngquant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pngquant/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pngquant/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pngquant/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pngquant",
    "version": "1.2.0",
    "description": "The pngquant utility as a readable/writable stream",
    "main": "lib/PngQuant.js",
    "directories": {
        "test": "test"
    },
    "optionalDependencies": {
        "pngquant-bin": "3.1.1"
    },
    "devDependencies": {
        "coveralls": "2.11.2",
        "istanbul": "0.3.15",
        "jshint": "2.8.0",
        "mocha": "2.4.5",
        "semver": "5.0.3",
        "sinon": "1.17.3",
        "unexpected": "10.11.1",
        "unexpected-sinon": "10.2.0",
        "unexpected-stream": "2.0.3"
    },
    "scripts": {
        "lint": "jshint .",
        "test": "mocha && npm run lint",
        "travis": "npm test && npm run coverage && (<coverage/lcov.info coveralls || true)",
        "coverage": "NODE_ENV=development istanbul cover _mocha -- --reporter dot && echo google-chrome coverage/lcov-report/index.html"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/papandreou/node-pngquant.git"
    },
    "keywords": [
        "pngquant",
        "png",
        "image",
        "optimization",
        "stream",
        "filter",
        "read/write",
        "duplex"
    ],
    "author": "Andreas Lind <andreas@one.com>",
    "license": "BSD-3-Clause",
    "dependencies": {
        "memoizeasync": "0.8.0",
        "which": "1.1.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
