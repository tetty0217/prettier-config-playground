prettier-config-playground ![GitHub package.json version](https://img.shields.io/github/package-json/v/tetty0217/prettier-config-playground) [![Package Release](https://github.com/tetty0217/prettier-config-playground/actions/workflows/release.yml/badge.svg?branch=main&event=status)](https://github.com/tetty0217/prettier-config-playground/actions/workflows/release.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)　
===================

JavaScript の技術検証（Playground）のリポジトリで使用するためのフォーマッタ設定

## Installation

```sh
# npm
$ npm i -D prettier

# yarn
$ yarn add -D prettier
```

## Usage

```sh
# npm
$ npm i -D @tetty0217/prettier-config-playground

# yarn
$ yarn add -D @tetty0217/prettier-config-playground
```

`.prettierrc.js`
```javascript
module.exports = {
    ...require('@tetty0217/prettier-config-playground'),
    ...your_configs
};

```
