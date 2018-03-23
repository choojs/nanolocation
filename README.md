# nanolocation [![stability][0]][1]
[![npm version][2]][3] [![build status][4]][5]
[![downloads][8]][9] [![js-standard-style][10]][11]

Small window.location library

## Usage
```js
var nanolocation = require('nanolocation')
var location = nanolocation()
console.log(location)
```

## API
### `location = nanolocation()`
Get the current `window.location.pathname` + `window.location.hash` as a
single path. E.g. a pathname of `/foo/bar/` and hash of `#baz` becomes
`/foo/bar/baz`.

## License
[MIT](https://tldrlegal.com/license/mit-license)

[0]: https://img.shields.io/badge/stability-experimental-orange.svg?style=flat-square
[1]: https://nodejs.org/api/documentation.html#documentation_stability_index
[2]: https://img.shields.io/npm/v/nanolocation.svg?style=flat-square
[3]: https://npmjs.org/package/nanolocation
[4]: https://img.shields.io/travis/choojs/nanolocation/master.svg?style=flat-square
[5]: https://travis-ci.org/choojs/nanolocation
[6]: https://img.shields.io/codecov/c/github/choojs/nanolocation/master.svg?style=flat-square
[7]: https://codecov.io/github/choojs/nanolocation
[8]: http://img.shields.io/npm/dm/nanolocation.svg?style=flat-square
[9]: https://npmjs.org/package/nanolocation
[10]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[11]: https://github.com/feross/standard
