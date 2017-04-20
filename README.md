# npmtest-jsftp

#### basic test coverage for  [jsftp (v1.5.5)](https://github.com/sergi/jsftp)  [![npm package](https://img.shields.io/npm/v/npmtest-jsftp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsftp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsftp.svg)](https://travis-ci.org/npmtest/node-npmtest-jsftp)

#### A sane FTP client implementation for NodeJS

[![NPM](https://nodei.co/npm/jsftp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsftp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsftp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsftp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsftp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsftp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsftp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsftp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsftp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsftp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsftp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsftp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsftp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsftp/build/test-report.html](https://npmtest.github.io/node-npmtest-jsftp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsftp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsftp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsftp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsftp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsftp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsftp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsftp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsftp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jsftp",
    "id": "jsftp",
    "version": "1.5.5",
    "description": "A sane FTP client implementation for NodeJS",
    "keywords": [
        "ftp",
        "protocol",
        "files",
        "server",
        "client",
        "async"
    ],
    "author": "Sergi Mansilla <sergi.mansilla@gmail.com> (http://sergimansilla.com)",
    "homepage": "https://github.com/sergi/jsftp",
    "repository": {
        "type": "git",
        "url": "https://github.com/sergi/jsftp.git"
    },
    "bugs": {
        "url": "https://github.com/sergi/jsftp/issues"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "ftp-response-parser": "^1.0.1",
        "once": "^1.3.3",
        "parse-listing": "^1.1.3",
        "stream-combiner": "^0.2.2",
        "unorm": "^1.4.1"
    },
    "devDependencies": {
        "concat-stream": "^1.5.0",
        "ftp-test-server": "0.0.2",
        "ftpd": "^0.2.15",
        "istanbul": "^0.3.22",
        "mocha": "^1.21.4",
        "mocha-istanbul": "0.2.0",
        "rimraf": "^2.2.8",
        "sinon": "^1.17.1"
    },
    "main": "lib/jsftp.js",
    "engines": {
        "node": ">=0.10"
    },
    "scripts": {
        "test": "mocha -R spec -t 5000",
        "clean": "rm -rf reports"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
