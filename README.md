# npmdoc-react-infinite

#### api documentation for  [react-infinite (v0.10.0)](https://github.com/seatgeek/react-infinite)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-infinite.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-infinite) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-infinite.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-infinite)

#### A browser-ready efficient scrolling container based on UITableView

[![NPM](https://nodei.co/npm/react-infinite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-infinite)

- [https://npmdoc.github.io/node-npmdoc-react-infinite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-infinite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-infinite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-infinite/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-infinite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-infinite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-infinite",
    "version": "0.10.0",
    "description": "A browser-ready efficient scrolling container based on UITableView",
    "main": "build/react-infinite.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/seatgeek/react-infinite"
    },
    "keywords": [
        "react",
        "react-component",
        "scrolling",
        "uitableview",
        "infinite"
    ],
    "author": "Gareth Tan",
    "license": "BSD-3-Clause",
    "bugs": {
        "url": "https://github.com/seatgeek/react-infinite/issues"
    },
    "browser": "build/react-infinite.js",
    "scripts": {
        "test": "node ./node_modules/.bin/jest",
        "lint": "./node_modules/.bin/eslint ./src --ext .jsx --ext .js",
        "fix": "./node_modules/.bin/eslint --fix --ext .jsx --ext .js ./src ./__tests__ ./pipeline",
        "typecheck": "./node_modules/.bin/flow version && ./node_modules/.bin/flow check",
        "verify": "npm test && npm run typecheck && npm run lint",
        "preversion": "npm run verify",
        "prepublish": "gulp release"
    },
    "jest": {
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "testPathDirs": [
            "<rootDir>/__tests__",
            "<rootDir>/src"
        ],
        "testPathIgnorePatterns": [
            "<rootDir>/__tests__/helpers"
        ],
        "testFileExtensions": [
            "js",
            "jsx"
        ],
        "unmockedModulePathPatterns": [
            "<rootDir>/node_modules/react"
        ],
        "collectCoverage": true,
        "verbose": true
    },
    "homepage": "https://github.com/seatgeek/react-infinite",
    "devDependencies": {
        "babel-eslint": "^4.0.7",
        "babel-jest": "^5.3.0",
        "babelify": "^6.3.0",
        "browserify": "^9.0.3",
        "coveralls": "^2.11.2",
        "del": "2.0.2",
        "envify": "3.4.0",
        "eslint": "1.9.0",
        "eslint-config-semistandard": "^5.0.0",
        "eslint-config-standard": "^4.1.0",
        "eslint-plugin-react": "^3.2.3",
        "eslint-plugin-standard": "^1.2.0",
        "flow-bin": "0.33.0",
        "gulp": "^3.8.8",
        "gulp-babel": "^5.2.1",
        "gulp-concat": "^2.4.3",
        "gulp-size": "^2.0.0",
        "gulp-sourcemaps": "^1.2.4",
        "gulp-uglify": "^1.0.1",
        "gulp-webserver": "^0.9.1",
        "jest-cli": "0.8.2",
        "moment": "^2.10.6",
        "react-addons-test-utils": "^15.0.0",
        "uglifyify": "3.0.1",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.0.0",
        "watch": "^0.16.0",
        "watchify": "^3.4.0",
        "yargs": "^1.3.2"
    },
    "dependencies": {
        "lodash.isarray": "3.0.4",
        "lodash.isfinite": "3.2.0",
        "object-assign": "4.0.1"
    },
    "peerDependencies": {
        "react": "^15.0.0",
        "react-dom": "^15.0.0"
    },
    "browserify": {
        "transform": [
            "envify"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
