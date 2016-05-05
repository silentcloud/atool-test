# atool-test

> `note`: If you want to run tests with browser, use version 0.4.x. 

[![NPM version](https://img.shields.io/npm/v/atool-test.svg?style=flat)](https://npmjs.org/package/atool-test)
[![Build Status](https://img.shields.io/travis/ant-tool/atool-test.svg?style=flat)](https://travis-ci.org/ant-tool/atool-test)
[![Coverage Status](https://img.shields.io/coveralls/ant-tool/atool-test.svg?style=flat)](https://coveralls.io/r/ant-tool/atool-test)

Simple configuration, makes you focus more on the writing tests.

## Built-in

- [mocha](http://mochajs.org/)
- [chai](http://chaijs.com/api)
- [sinon](http://sinonjs.org/)

## Usage

```bash
npm install atool-test --save-dev
```
```json
"srcipts": {
  "test": "atool-test"
}
```

## Options

- `--coverage`: coverage output;
- support mocha cli options (`--bail`, `--timeout`, `--watch`, `--recursive`...) 

## Custom testDir

default tests dir `test`, cutom dir `atool-test ${customDirName}`

