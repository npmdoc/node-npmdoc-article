# npmdoc-article

#### api documentation for  [article (v1.1.2)](https://github.com/AndreasMadsen/article)  [![npm package](https://img.shields.io/npm/v/npmdoc-article.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-article) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-article.svg)](https://travis-ci.org/npmdoc/node-npmdoc-article)

#### Analyze a stream of HTML and outsputs the article title, text, and image

[![NPM](https://nodei.co/npm/article.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/article)

- [https://npmdoc.github.io/node-npmdoc-article/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-article/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-article/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-article/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-article/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-article/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andreas Madsen"
    },
    "bugs": {
        "url": "https://github.com/AndreasMadsen/article/issues"
    },
    "dependencies": {
        "editdistance": "0.2.x",
        "entities": "1.1.x",
        "fusspos": "0.2.x",
        "htmlparser2": "3.8.x",
        "summary": "0.3.x",
        "ttest": "0.3.x",
        "worddiff": "0.3.x"
    },
    "description": "Analyze a stream of HTML and outsputs the article title, text, and image",
    "devDependencies": {
        "async": "0.9.x",
        "difflet": "0.2.x",
        "endpoint": "0.4.x",
        "feedparser": "0.19.x",
        "interpreted": "0.5.x",
        "mappoint": "0.2.x",
        "request": "2.23.x",
        "st": "0.5.x",
        "startpoint": "0.3.x",
        "tap": "0.6.x",
        "text-table": "0.2.x",
        "ws": "0.7.x"
    },
    "directories": {},
    "dist": {
        "shasum": "d3f09e44a834a96d6e0534247f58aac78327a6ca",
        "tarball": "https://registry.npmjs.org/article/-/article-1.1.2.tgz"
    },
    "gitHead": "5e726924bb1fd17c1e04498a827b2d961db56b09",
    "homepage": "https://github.com/AndreasMadsen/article",
    "keywords": [
        "article",
        "reader"
    ],
    "license": "MIT",
    "main": "./lib/article.js",
    "maintainers": [
        {
            "name": "andreasmadsen"
        }
    ],
    "name": "article",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/AndreasMadsen/article.git"
    },
    "scripts": {
        "test": "tap test/reallife/runner.js test/internal/*"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
