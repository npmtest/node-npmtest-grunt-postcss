# npmtest-grunt-postcss

#### basic test coverage for  grunt-postcss (v0.8.0)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-postcss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-postcss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-postcss.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-postcss)

#### Apply several post-processors to your CSS using PostCSS

[![NPM](https://nodei.co/npm/grunt-postcss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-postcss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-postcss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-postcss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-postcss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-postcss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-postcss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-postcss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-postcss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-postcss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-postcss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-postcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-postcss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-postcss/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-postcss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-postcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-postcss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-postcss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-postcss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-postcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-postcss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-postcss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-postcss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-postcss",
    "version": "0.8.0",
    "description": "Apply several post-processors to your CSS using PostCSS",
    "author": {
        "name": "Dmitry Nikitenko"
    },
    "repository": "nDmitry/grunt-postcss",
    "license": "MIT",
    "engines": {
        "node": ">= 0.12.0"
    },
    "scripts": {
        "test": "grunt test"
    },
    "keywords": [
        "gruntplugin",
        "postcss-runner",
        "css",
        "postprocessor",
        "postcss"
    ],
    "files": [
        "tasks",
        "LICENSE"
    ],
    "dependencies": {
        "chalk": "^1.0.0",
        "diff": "^2.0.2",
        "postcss": "^5.0.0"
    },
    "devDependencies": {
        "cssnano": "^3.3.1",
        "grunt": "^0.4.5",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^0.4.0",
        "load-grunt-tasks": "^3.1.0",
        "postcss-scss": "^0.1.0",
        "time-grunt": "^1.1.0"
    },
    "peerDependencies": {
        "grunt": ">=0.4.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
