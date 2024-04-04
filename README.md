# @npmtuanmap2024/consequatur-veniam-optio <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @npmtuanmap2024/consequatur-veniam-optio
```

## Usage/Examples

```js
var regexTester = require('@npmtuanmap2024/consequatur-veniam-optio');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@npmtuanmap2024/consequatur-veniam-optio
[npm-version-svg]: https://versionbadg.es/ljharb/@npmtuanmap2024/consequatur-veniam-optio.svg
[deps-svg]: https://david-dm.org/ljharb/@npmtuanmap2024/consequatur-veniam-optio.svg
[deps-url]: https://david-dm.org/ljharb/@npmtuanmap2024/consequatur-veniam-optio
[dev-deps-svg]: https://david-dm.org/ljharb/@npmtuanmap2024/consequatur-veniam-optio/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@npmtuanmap2024/consequatur-veniam-optio#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@npmtuanmap2024/consequatur-veniam-optio.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@npmtuanmap2024/consequatur-veniam-optio.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@npmtuanmap2024/consequatur-veniam-optio.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@npmtuanmap2024/consequatur-veniam-optio
[codecov-image]: https://codecov.io/gh/ljharb/@npmtuanmap2024/consequatur-veniam-optio/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@npmtuanmap2024/consequatur-veniam-optio/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@npmtuanmap2024/consequatur-veniam-optio
[actions-url]: https://github.com/npmtuanmap2024/consequatur-veniam-optio/actions
