# extend2

Forked from [node-extend], the difference is overriding array as primitive when deep clone.

[![NPM version][npm-image]][npm-url]
[![Node.js CI](https://github.com/eggjs/extend2/actions/workflows/nodejs.yml/badge.svg)](https://github.com/eggjs/extend2/actions/workflows/nodejs.yml)
[![Test coverage][codecov-image]][codecov-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/extend2.svg?style=flat-square
[npm-url]: https://npmjs.org/package/extend2
[codecov-image]: https://codecov.io/gh/eggjs/extend2/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/eggjs/extend2
[snyk-image]: https://snyk.io/test/npm/extend2/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/extend2
[download-image]: https://img.shields.io/npm/dm/extend2.svg?style=flat-square
[download-url]: https://npmjs.org/package/extend2

## Usage

```ts
import { extend } from 'extend2';

// for deep clone
extend(true, {}, object1, objectN);
```

## License

`extend2` is licensed under the [MIT License](LICENSE).

## Acknowledgements

All credit to the jQuery authors for perfecting this amazing utility.

Ported to Node.js by [Stefan Thomas][github-justmoon] with contributions by [Jonathan Buchanan][github-insin] and [Jordan Harband][github-ljharb].

[github-justmoon]: https://github.com/justmoon
[github-insin]: https://github.com/insin
[github-ljharb]: https://github.com/ljharb
[node-extend]: https://github.com/justmoon/node-extend
