# atool-test

[![NPM version](https://img.shields.io/npm/v/atool-test.svg?style=flat)](https://npmjs.org/package/atool-test)
[![Build Status](https://img.shields.io/travis/ant-tool/atool-test.svg?style=flat)](https://travis-ci.org/ant-tool/atool-test)
[![Coverage Status](https://img.shields.io/coveralls/ant-tool/atool-test.svg?style=flat)](https://coveralls.io/r/ant-tool/atool-test)
[![NPM downloads](http://img.shields.io/npm/dm/atool-test.svg?style=flat)](https://npmjs.org/package/atool-test)


## Built-in

- [mocha](http://mochajs.org/)
- [chai](http://chaijs.com/api)
- [sinon](http://sinonjs.org/)

## Usage

>  Add `-test.js` suffix with your test files

```
"srcipts": {
  "test": "atool-test"
}
```

with options:

```
atool-test --port 9888 --assert shouldjs --keep
```

## Options

- `-p, --port`: server port, default is 9876;
- `-a, --assert`: run test with custom assert library <expectjs、shouldjs、chaijs(default)>
- `-k, --keep`: keep process after tests, for browser test

## Custom Assert

>  atool-test --assert expectjs

- expectjs: `npm install expect.js --save-dev`
- shouldjs: `npm install should --save-dev`

## Browser Test

  Run with `--keep` option, open `http://127.0.0.1:${port}/tests/runner.html` in your browser.

