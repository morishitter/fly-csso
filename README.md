<div align="center">
  <a href="http://github.com/flyjs/fly">
    <img width=200px  src="https://cloud.githubusercontent.com/assets/8317250/8733685/0be81080-2c40-11e5-98d2-c634f076ccd7.png">
  </a>
</div>

> [CSSO](https://github.com/css/csso) plugin for _[Fly][fly]_.

[![][fly-badge]][fly]
[![npm package][npm-ver-link]][releases]
[![][dl-badge]][npm-pkg-link]
[![][travis-badge]][travis-link]
[![][mit-badge]][mit]

## Usage
> Check out the [documentation](https://github.com/css/csso) to see the available options.

### Install

```a
npm install -D fly-csso
```

### Example

```js
export default function* () {
  yield this
    .source("src/*.css")
    .csso()
    .target("dist")
}
```

# License

[MIT][mit] © [Masaaki Morishita][author] et [al][contributors]


[mit]:          http://opensource.org/licenses/MIT
[author]:       http://github.com/morishitter
[contributors]: https://github.com/morishitter/fly-csso/graphs/contributors
[releases]:     https://github.com/morishitter/fly-csso/releases
[fly]:          https://www.github.com/flyjs/fly
[fly-badge]:    https://img.shields.io/badge/fly-JS-05B3E1.svg?style=flat-square
[mit-badge]:    https://img.shields.io/badge/license-MIT-444444.svg?style=flat-square
[npm-pkg-link]: https://www.npmjs.org/package/fly-csso
[npm-ver-link]: https://img.shields.io/npm/v/fly-csso.svg?style=flat-square
[dl-badge]:     http://img.shields.io/npm/dm/fly-csso.svg?style=flat-square
[travis-link]:  https://travis-ci.org/morishitter/fly-csso
[travis-badge]: http://img.shields.io/travis/morishitter/fly-csso.svg?style=flat-square
