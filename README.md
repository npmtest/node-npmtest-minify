# npmtest-minify

#### basic test coverage for  [minify (v2.0.13)](http://coderaiser.github.io/minify)  [![npm package](https://img.shields.io/npm/v/npmtest-minify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-minify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-minify.svg)](https://travis-ci.org/npmtest/node-npmtest-minify)

#### Minifier of js, css, html and img

[![NPM](https://nodei.co/npm/minify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-minify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-minify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-minify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-minify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-minify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-minify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-minify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-minify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-minify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-minify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-minify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-minify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-minify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-minify/build/test-report.html](https://npmtest.github.io/node-npmtest-minify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-minify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-minify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-minify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-minify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-minify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "coderaiser",
        "url": "https://github.com/coderaiser"
    },
    "bin": {
        "minify": "bin/minify.js"
    },
    "bugs": {
        "url": "https://github.com/coderaiser/minify/issues"
    },
    "dependencies": {
        "clean-css": "~3.4.1",
        "css-b64-images": "~0.2.5",
        "debug": "^2.3.0",
        "execon": "~1.2.0",
        "html-minifier": "^3.0.1",
        "rendy": "~1.1.0",
        "tomas": "~1.0.0",
        "try-catch": "~1.0.0",
        "uglify-js": "^2.7.0"
    },
    "description": "Minifier of js, css, html and img",
    "devDependencies": {
        "jscs": "^3.0.3",
        "jshint": "^2.8.0",
        "tape": "^4.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e4f75cb34e919ef1ccc60bf4f2aec0b9b7863ab9",
        "tarball": "https://registry.npmjs.org/minify/-/minify-2.0.13.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "eeaa345e390ff0029c8da18ba6aee404a9b498eb",
    "homepage": "http://coderaiser.github.io/minify",
    "keywords": [
        "minify",
        "minimize",
        "js",
        "css",
        "img",
        "html",
        "base64"
    ],
    "license": "MIT",
    "main": "lib/minify",
    "maintainers": [
        {
            "name": "coderaiser"
        }
    ],
    "name": "minify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/coderaiser/minify.git"
    },
    "scripts": {
        "jscs": "jscs --esnext lib test",
        "jscs-fix": "jscs --fix lib test",
        "jshint": "jshint lib test",
        "lint": "npm run jshint && npm run jscs",
        "test": "tape test/minify.js"
    },
    "version": "2.0.13"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
