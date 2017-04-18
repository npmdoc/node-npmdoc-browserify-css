# npmdoc-browserify-css

#### api documentation for  [browserify-css (v0.10.0)](http://cheton.github.io/browserify-css/)  [![npm package](https://img.shields.io/npm/v/npmdoc-browserify-css.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browserify-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browserify-css.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browserify-css)

#### A Browserify transform for bundling, rebasing, inlining, and minifying CSS files

[![NPM](https://nodei.co/npm/browserify-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserify-css)

- [https://npmdoc.github.io/node-npmdoc-browserify-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserify-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserify-css/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browserify-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browserify-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cheton Wu"
    },
    "browser": "./browser.js",
    "bugs": {
        "url": "https://github.com/cheton/browserify-css/issues"
    },
    "dependencies": {
        "clean-css": "2.2.x",
        "concat-stream": "1.4.x",
        "css": "1.6.x",
        "find-node-modules": "^1.0.1",
        "lodash": "3.6.x",
        "mime": "~1.2.11",
        "through2": "0.6.x"
    },
    "description": "A Browserify transform for bundling, rebasing, inlining, and minifying CSS files",
    "devDependencies": {
        "browserify": "^12.0.1",
        "coveralls": "^2.11.8",
        "del": "^1.1.1",
        "exorcist": "^0.1.6",
        "fs-extra": "^0.18.0",
        "gulp": "^3.9.0",
        "gulp-jshint": "^1.9.2",
        "gulp-util": "^3.0.4",
        "jsdom": "^8.1.0",
        "require-dir": "^0.3.0",
        "run-sequence": "^1.0.2",
        "tap": "^5.7.0",
        "vinyl-source-stream": "^1.1.0",
        "yargs": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f3eb0f35cbe1fee02a03de2b8c83c5d499dd794d",
        "tarball": "https://registry.npmjs.org/browserify-css/-/browserify-css-0.10.0.tgz"
    },
    "gitHead": "32f461bce3461ae05a72f0c056e35035ab8f24f0",
    "homepage": "http://cheton.github.io/browserify-css/",
    "keywords": [
        "browser",
        "browserify",
        "browserify-transform",
        "css",
        "dom",
        "minify",
        "transform"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "cheton"
        }
    ],
    "name": "browserify-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cheton/browserify-css.git"
    },
    "scripts": {
        "build": "gulp",
        "coveralls": "tap --coverage --coverage-report=text-lcov test/*.js | node_modules/.bin/coveralls",
        "prepublish": "npm run build && npm test",
        "test": "gulp && node_modules/.bin/tap --coverage test/*.js"
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
