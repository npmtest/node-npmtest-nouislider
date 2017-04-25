# npmtest-nouislider

#### basic test coverage for  [nouislider (v9.2.0)](https://github.com/leongersen/noUiSlider#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nouislider.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nouislider) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nouislider.svg)](https://travis-ci.org/npmtest/node-npmtest-nouislider)

#### noUiSlider is lightweight JavaScript range slider, originally developed to be a jQuery UI alternative.

[![NPM](https://nodei.co/npm/nouislider.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nouislider)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nouislider/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nouislider/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nouislider/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nouislider/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nouislider/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nouislider/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nouislider/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nouislider/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nouislider/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nouislider/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nouislider/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nouislider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nouislider/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nouislider/build/test-report.html](https://npmtest.github.io/node-npmtest-nouislider/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nouislider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nouislider/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nouislider/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nouislider/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nouislider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nouislider/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nouislider/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nouislider/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/leongersen/noUiSlider/issues"
    },
    "dependencies": {},
    "description": "noUiSlider is lightweight JavaScript range slider, originally developed to be a jQuery UI alternative.",
    "devDependencies": {
        "blanket": "1.1.7",
        "browser-sync": "2.9.3",
        "grunt": "~0.4.1",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-compress": "^0.11.0",
        "grunt-contrib-concat": "^0.5.0",
        "grunt-contrib-copy": "^0.5.0",
        "grunt-contrib-cssmin": "^0.10.0",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-less": "^1.4.0",
        "grunt-contrib-qunit": "^1.2.0",
        "grunt-contrib-uglify": "^0.5.1",
        "onchange": "2.0.0",
        "simulant": "0.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "e87c507de2b0b4d075038b5a42547c7dbbebaf69",
        "tarball": "https://registry.npmjs.org/nouislider/-/nouislider-9.2.0.tgz"
    },
    "gitHead": "06ce7f5ebd66aa533752b0ff6c9d1c2272191d5c",
    "homepage": "https://github.com/leongersen/noUiSlider#readme",
    "license": "WTFPL",
    "main": "distribute/nouislider",
    "maintainers": [
        {
            "name": "approach"
        },
        {
            "name": "leongersen"
        }
    ],
    "name": "nouislider",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/leongersen/noUiSlider.git"
    },
    "scripts": {
        "build": "grunt create",
        "dev": "./scripts/dev.sh",
        "serve-tests": "browser-sync start --server . --startPath tests/slider.html --files 'distribute/, tests/*.js'",
        "test": "grunt lint",
        "watch:js": "npm run build && onchange 'src/js/*.js' 'src/*.css' -- npm run build"
    },
    "style": "distribute/nouislider.min.css",
    "version": "9.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
