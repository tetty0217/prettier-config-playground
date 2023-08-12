prettier-config-playground 
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
