# htmldeps

[![Greenkeeper badge](https://badges.greenkeeper.io/ForbesLindesay/htmldeps.svg)](https://greenkeeper.io/)

Detect the dependencies of an html file (not recursive)

## Installation

    npm install htmldeps

## Usage

```js
var detect = require('htmldeps')
var src = '<script src="foo.js"></script>'
var deps = detect(src)

// => ['foo.js']
```

## License

  MIT