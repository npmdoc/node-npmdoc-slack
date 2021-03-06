# npmdoc-slack

#### api documentation for  [slack (v8.2.7)](https://github.com/smallwins/slack#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-slack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-slack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-slack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-slack)

#### Slack API client written in JS

[![NPM](https://nodei.co/npm/slack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slack)

- [https://npmdoc.github.io/node-npmdoc-slack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-slack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-slack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian LeRoux"
    },
    "browser": {
        "./methods/rtm.client.js": "./methods/rtm.client-browser.js",
        "./test/_env.js": "./test/_env-browser.js"
    },
    "bugs": {
        "url": "https://github.com/smallwins/slack/issues"
    },
    "dependencies": {
        "tiny-json-http": "^5.1.0",
        "ws": "^1.1.4"
    },
    "description": "Slack API client written in JS",
    "devDependencies": {
        "async": "^2.1.2",
        "babel-cli": "^6.3.15",
        "babel-plugin-add-module-exports": "^0.1.1",
        "babel-preset-es2015": "^6.3.13",
        "babelify": "^7.2.0",
        "browser-run": "^4.0.1",
        "browserify": "^14.1.0",
        "chalk": "^1.1.1",
        "cheerio": "^0.22.0",
        "cpr": "^1.1.2",
        "envify": "^3.4.0",
        "glob": "^7.0.5",
        "lodash": "^4.5.0",
        "mustache": "^2.2.1",
        "node-env-file": "^0.1.8",
        "request": "^2.78.0",
        "rimraf": "^2.5.3",
        "tap": "^5.8.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7a795a3e5e8482d64075aae88e11f04f29358ba1",
        "tarball": "https://registry.npmjs.org/slack/-/slack-8.2.7.tgz"
    },
    "gitHead": "3e36da7a911bd3d4138aae507ad9eca7c967310f",
    "homepage": "https://github.com/smallwins/slack#readme",
    "keywords": [
        "slack",
        "api",
        "client"
    ],
    "license": "Apache-2.0",
    "main": "methods/index",
    "maintainers": [
        {
            "name": "brianleroux"
        },
        {
            "name": "dam"
        },
        {
            "name": "matthewmueller"
        },
        {
            "name": "mbrevoort"
        }
    ],
    "name": "slack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/smallwins/slack.git"
    },
    "scripts": {
        "btest": "npm run build && ./scripts/test-browser | browser-run | tap-spec",
        "build": "rimraf methods && babel src --out-dir methods && cpr src/api.json methods/api.json",
        "generate": "./scripts/generate-all",
        "prepublish": "npm run build",
        "start": "npm run build && ./scripts/repl",
        "t": "npm run build && ./scripts/t",
        "test": "npm run build && ./scripts/test"
    },
    "version": "8.2.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
