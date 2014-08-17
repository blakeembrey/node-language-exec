# Language Exec

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Gittip][gittip-image]][gittip-url]

Execute a file in any programming language based on [language-command](https://github.com/blakeembrey/node-language-command).

## Installation

```
npm install language-exec --save
```

## Usage

```javascript
var exec = require('language-exec');

exec('JavaScript', 'test.js', function (err, stdout, stderr) {
  console.log(stdout);
});
```

## License

MIT

[npm-image]: https://img.shields.io/npm/v/language-command.svg?style=flat
[npm-url]: https://npmjs.org/package/language-command
[travis-image]: https://img.shields.io/travis/blakeembrey/node-language-command.svg?style=flat
[travis-url]: https://travis-ci.org/blakeembrey/node-language-command
[coveralls-image]: https://img.shields.io/coveralls/blakeembrey/node-language-command.svg?style=flat
[coveralls-url]: https://coveralls.io/r/blakeembrey/node-language-command?branch=master
[gittip-image]: https://img.shields.io/gittip/blakeembrey.svg?style=flat
[gittip-url]: https://www.gittip.com/blakeembrey
