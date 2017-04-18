# npmtest-sander

#### test coverage for  [sander (v0.6.0)](https://github.com/rich-harris/sander#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sander.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sander) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sander.svg)](https://travis-ci.org/npmtest/node-npmtest-sander)

#### Promise-based power tool for common filesystem tasks

[![NPM](https://nodei.co/npm/sander.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sander)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sander/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sander/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sander/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sander/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sander/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sander/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sander/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sander/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sander/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sander/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sander/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sander/build/test-report.html](https://npmtest.github.io/node-npmtest-sander/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sander/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sander/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sander/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sander/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sander/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sander/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sander/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sander/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rich Harris"
    },
    "bugs": {
        "url": "https://github.com/rich-harris/sander/issues"
    },
    "dependencies": {
        "graceful-fs": "^4.1.3",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.2"
    },
    "description": "Promise-based power tool for common filesystem tasks",
    "devDependencies": {
        "buffer-crc32": "^0.2.5",
        "mocha": "^3.2.0",
        "rollup": "^0.36.4",
        "rollup-plugin-buble": "^0.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "af1624cd7fb6dfad98ebef565319f920078da925",
        "tarball": "https://registry.npmjs.org/sander/-/sander-0.6.0.tgz"
    },
    "files": [
        "dist",
        "README.md"
    ],
    "gitHead": "000590a0a4a954e0488c028fad4b7ca801023aee",
    "homepage": "https://github.com/rich-harris/sander#readme",
    "jsnext:main": "dist/sander.es.js",
    "license": "MIT",
    "main": "dist/sander.cjs.js",
    "maintainers": [
        {
            "name": "rich_harris"
        }
    ],
    "name": "sander",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rich-harris/sander.git"
    },
    "scripts": {
        "build": "rollup -c",
        "prepublish": "npm test",
        "pretest": "npm run build",
        "test": "mocha"
    },
    "version": "0.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
