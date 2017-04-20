# npmdoc-echarts

#### api documentation for  [echarts (v3.5.3)](http://echarts.baidu.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-echarts.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-echarts) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-echarts.svg)](https://travis-ci.org/npmdoc/node-npmdoc-echarts)

#### A powerful charting and visualization library for browser

[![NPM](https://nodei.co/npm/echarts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/echarts)

- [https://npmdoc.github.io/node-npmdoc-echarts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-echarts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-echarts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-echarts/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-echarts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-echarts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "echarts",
    "version": "3.5.3",
    "description": "A powerful charting and visualization library for browser",
    "keywords": [
        "visualization",
        "canvas"
    ],
    "homepage": "http://echarts.baidu.com/",
    "author": [
        {
            "name": "Kenner"
        },
        {
            "name": "Yi Shen",
            "url": "https://github.com/pissang"
        },
        {
            "name": "Shuang Su",
            "url": "https://github.com/100pah"
        }
    ],
    "contributors": [
        {
            "name": "erik"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/ecomfe/echarts.git"
    },
    "scripts": {
        "prepublish": "node build/amd2common.js"
    },
    "dependencies": {
        "zrender": "^3.4.3"
    },
    "devDependencies": {
        "coordtransform": "^2.0.2",
        "escodegen": "^1.8.0",
        "esprima": "^2.7.2",
        "estraverse": "^4.1.1",
        "fs-extra": "^0.26.5",
        "glob": "^7.0.0",
        "webpack": "^1.12.13",
        "zrender": "^3.4.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
