# api documentation for  [gulp-shell (v0.6.3)](https://github.com/sun-zheng-an/gulp-shell)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-shell.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-shell) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-shell.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-shell)
#### A handy command line interface for gulp

[![NPM](https://nodei.co/npm/gulp-shell.png?downloads=true)](https://www.npmjs.com/package/gulp-shell)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-shell/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-shell_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-shell/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-gulp-shell/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Sun Zheng'an"
    },
    "bugs": {
        "url": "https://github.com/sun-zheng-an/gulp-shell/issues"
    },
    "dependencies": {
        "async": "^2.1.5",
        "gulp-util": "^3.0.8",
        "lodash": "^4.17.4",
        "through2": "^2.0.3"
    },
    "description": "A handy command line interface for gulp",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.16",
        "gulp": "^3.9.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "mocha-lcov-reporter": "^1.3.0",
        "standard": "^8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2eaa6edfffa8bdff7a8f0b9f9852876f33331c6b",
        "tarball": "https://registry.npmjs.org/gulp-shell/-/gulp-shell-0.6.3.tgz"
    },
    "engines": {
        "node": ">=4.8.0 <5.0.0 || >=5.7.0"
    },
    "gitHead": "48f79d1629ddb760934decd7c2d64aac52e61f6d",
    "homepage": "https://github.com/sun-zheng-an/gulp-shell",
    "keywords": [
        "gulpplugin",
        "gulp",
        "shell",
        "command"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "sun-zheng-an",
            "email": "sun.zheng.an.0@gmail.com"
        }
    ],
    "name": "gulp-shell",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sun-zheng-an/gulp-shell.git"
    },
    "scripts": {
        "coveralls": "gulp coveralls",
        "test": "gulp test lint"
    },
    "version": "0.6.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-shell](#apidoc.module.gulp-shell)
1.  [function <span class="apidocSignatureSpan">gulp-shell.</span>task (commands, options)](#apidoc.element.gulp-shell.task)



# <a name="apidoc.module.gulp-shell"></a>[module gulp-shell](#apidoc.module.gulp-shell)

#### <a name="apidoc.element.gulp-shell.task"></a>[function <span class="apidocSignatureSpan">gulp-shell.</span>task (commands, options)](#apidoc.element.gulp-shell.task)
- description and source-code
```javascript
(commands, options) => (done) => {
  runCommands(normalizeCommands(commands), normalizeOptions(options), null, done)
}
```
- example usage
```shell
...

## Usage

'''js
const gulp = require('gulp')
const shell = require('gulp-shell')

gulp.task('example', () => {
  return gulp.src('*.js', {read: false})
  .pipe(shell([
    'echo <%= file.path %>'
  ]))
})
'''
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
