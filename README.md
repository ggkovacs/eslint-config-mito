# [eslint](http://eslint.org)-config-mito [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage Status][coverage-image]][coverage-url]
Version: **8.0.0**

This package provides Mito's .eslintrc as an extensible shared config.

## Usage

We export three ESLint configurations for your usage.

### eslint-config-mito

Lints EcmaScript 6+. Only requires `eslint`.

1. `npm install --save-dev eslint eslint-config-mito`
2. add `"extends": "mito"` to your [.eslintrc](http://eslint.org/docs/user-guide/configuring.html#configuration-file-formats)
```js
{
  "extends": "mito"
}
```

### eslint-config-mito/legacy

Lints EcmaScript 5 and below. Only requires `eslint`.

1. `npm install --save-dev eslint eslint-config-mito`
2. add `"extends": "mito/legacy"` to your [.eslintrc](http://eslint.org/docs/user-guide/configuring.html#configuration-file-formats)
```js
{
  "extends": "mito/legacy"
}
```

See [Mito's documentation](https://github.com/hellowearemito/eslint-config-mito/tree/master/docs) and
the [ESlint config docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files)
for more information.

## License
MIT © 2017 Mito (info@mito.hu)

[npm-image]: https://badge.fury.io/js/eslint-config-mito.svg
[npm-url]: https://npmjs.org/package/eslint-config-mito
[travis-image]: https://travis-ci.org/hellowearemito/eslint-config-mito.svg?branch=master
[travis-url]: https://travis-ci.org/hellowearemito/eslint-config-mito
[coverage-image]: https://coveralls.io/repos/hellowearemito/eslint-config-mito/badge.svg?service=github&branch=master
[coverage-url]: https://coveralls.io/github/hellowearemito/eslint-config-mito?branch=master
