# @erboladaiorg/voluptate-alias-voluptate <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Does the current environment have `import()` support?

At the time of this writing, node v12.17+, v13.2+ and v14.0+ has support for dynamic [`import()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import#dynamic_imports); the syntax is supported in node v10+.

The former can be checked in the package‘s main export, which is an `async function` that returns a boolean indicating if the current environment fully supports dynamic import. Note that in node v12.17 - v12.19 and v13.4 - v13.13, an ExperimentalWarning will be logged.

The latter can be checked with `'@erboladaiorg/voluptate-alias-voluptate/syntax'`, which is a function that returns a boolean indicating if the current environment supports parsing the syntax of dynamic import.

## Tests

Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@erboladaiorg/voluptate-alias-voluptate
[npm-version-svg]: https://versionbadg.es/inspect-js/@erboladaiorg/voluptate-alias-voluptate.svg
[deps-svg]: https://david-dm.org/inspect-js/@erboladaiorg/voluptate-alias-voluptate.svg
[deps-url]: https://david-dm.org/inspect-js/@erboladaiorg/voluptate-alias-voluptate
[dev-deps-svg]: https://david-dm.org/inspect-js/@erboladaiorg/voluptate-alias-voluptate/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@erboladaiorg/voluptate-alias-voluptate#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/voluptate-alias-voluptate.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/voluptate-alias-voluptate.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/voluptate-alias-voluptate.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/voluptate-alias-voluptate
[codecov-image]: https://codecov.io/gh/inspect-js/@erboladaiorg/voluptate-alias-voluptate/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@erboladaiorg/voluptate-alias-voluptate/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@erboladaiorg/voluptate-alias-voluptate
[actions-url]: https://github.com/erboladaiorg/voluptate-alias-voluptate/actions
