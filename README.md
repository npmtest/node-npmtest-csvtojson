# test coverage for  [csvtojson (v1.1.4)](http://keyangxiang.com/blog/csv2json/)  [![npm package](https://img.shields.io/npm/v/npmtest-csvtojson.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csvtojson) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csvtojson.svg)](https://travis-ci.org/npmtest/node-npmtest-csvtojson)
#### A tool concentrating on converting csv data to JSON with customised parser supporting

[![NPM](https://nodei.co/npm/csvtojson.png?downloads=true)](https://www.npmjs.com/package/csvtojson)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csvtojson/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csvtojson/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csvtojson/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csvtojson/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csvtojson/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csvtojson/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csvtojson/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csvtojson/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-csvtojson/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-csvtojson/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-csvtojson%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csvtojson/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csvtojson/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-csvtojson%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csvtojson/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csvtojson/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csvtojson/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Keyang Xiang",
        "email": "keyang.xiang@gmail.com"
    },
    "bin": {
        "csvtojson": "./bin/csvtojson"
    },
    "bugs": {
        "url": "https://github.com/Keyang/node-csvtojson/issues"
    },
    "contributors": [
        {
            "name": "Daniel Cohen",
            "email": "dcohenb@gmail.com",
            "url": "https://github.com/dcohenb"
        },
        {
            "name": "Trang",
            "email": "trangtungn@gmail.com",
            "url": "https://github.com/trangtungn"
        },
        {
            "name": "Matthias Lienau",
            "email": "matthias@mlienau.de",
            "url": "https://github.com/atufkas"
        },
        {
            "name": "Alec Fenichel",
            "email": "alec.fenichel@gmail.com",
            "url": "https://github.com/fenichelar"
        },
        {
            "name": "Blake Blackshear",
            "url": "https://github.com/blakeblackshear"
        },
        {
            "name": "Dimitri Kennedy",
            "email": "dimitrikennedy@gmail.com",
            "url": "https://github.com/roodboi"
        },
        {
            "url": "https://github.com/markwithers"
        },
        {
            "name": "Robert Porter",
            "url": "https://github.com/colarob"
        },
        {
            "name": "Jessica Good",
            "url": "https://github.com/jessicagood"
        },
        {
            "url": "https://github.com/jondayft"
        },
        {
            "name": "Dane Petersen",
            "url": "https://github.com/thegreatsunra"
        },
        {
            "name": "Jimi Ford",
            "url": "https://github.com/JimiHFord"
        },
        {
            "name": "Hocine Moukaideche",
            "url": "https://github.com/Off76"
        },
        {
            "name": "Keyang Xiang",
            "email": "keyang.xiang@gmail.com",
            "url": "https://github.com/Keyang"
        },
        {
            "name": "Ionică Bizău",
            "email": "contact@ionicabizau.net",
            "url": "https://github.com/IonicaBizau"
        },
        {
            "name": "Sean Lang",
            "email": "slang800@gmail.com",
            "url": "https://github.com/slang800"
        },
        {
            "name": "Tom Dodson",
            "email": "t3.dodson@gmail.com",
            "url": "https://github.com/t3dodson"
        },
        {
            "name": "Jeff Johnson",
            "url": "https://github.com/jeffcjohnson"
        },
        {
            "name": "Amila Welihinda",
            "email": "amilajack@gmail.com",
            "url": "https://github.com/amilajack"
        },
        {
            "name": "Zsolt R. Molnar",
            "url": "https://github.com/molnarzs"
        }
    ],
    "dependencies": {
        "lodash": "^4.17.3"
    },
    "description": "A tool concentrating on converting csv data to JSON with customised parser supporting",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-browserify": "^4.0.1",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-git": "^0.3.5",
        "grunt-madge": "0.0.6",
        "grunt-mocha-test": "^0.12.7",
        "grunt-newer": "^1.1.0",
        "imgur": "^0.1.5",
        "load-grunt-tasks": "^3.4.0",
        "minimist": "^1.2.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "8deafcd6e78dac01812a34ed022670e16d402fe7",
        "tarball": "https://registry.npmjs.org/csvtojson/-/csvtojson-1.1.4.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "590d5580348ede58e916277d8167f3f6e20f4219",
    "homepage": "http://keyangxiang.com/blog/csv2json/",
    "keywords": [
        "csv",
        "csv parser",
        "parse csv",
        "csvtojson",
        "json",
        "csv to json",
        "csv convert",
        "tojson",
        "convert csv to json",
        "csv-json"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "keyang",
            "email": "keyang.xiang@gmail.com"
        }
    ],
    "name": "csvtojson",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Keyang/node-csvtojson.git"
    },
    "scripts": {
        "test": "mocha ./test -R spec",
        "test-all": "mocha  ./test -R spec && CSV_WORKER=3 mocha ./test -R spec ",
        "test-debug": "mocha debug ./test -R spec"
    },
    "version": "1.1.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
