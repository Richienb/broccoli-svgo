# [broccoli](https://github.com/joliss/broccoli)-svgo [![Build Status](https://travis-ci.org/sindresorhus/broccoli-svgo.svg?branch=master)](https://travis-ci.org/sindresorhus/broccoli-svgo)

> Minify SVG using [SVGO](https://github.com/svg/svgo)

*Issues with the output should be reported on the SVGO [issue tracker](https://github.com/svg/svgo/issues).*


## Install

```
$ npm install --save-dev broccoli-svgo
```


## Usage

```js
var svgo = require('broccoli-svgo');
tree = svgo(tree, options);
```


## API

### svgo(tree, [options])

#### options

[Options](https://github.com/sindresorhus/grunt-svgmin#available-optionsplugins) are passed to `SVGO`.


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
