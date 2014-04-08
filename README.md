# Language Exec

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
