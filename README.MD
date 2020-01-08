<p align="center">
    <img src="http://upload.ouliu.net/i/2020010816382426yew.png" width="240">
</p>

# stylelint-plugin-chowa-standard

[![npm](https://img.shields.io/npm/v/stylelint-plugin-chowa-standard.svg)](https://www.npmjs.com/package/stylelint-plugin-chowa-standard)
[![npm](https://img.shields.io/npm/dm/stylelint-plugin-chowa-standard.svg)](https://www.npmjs.com/package/stylelint-plugin-chowa-standard)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://opensource.org/licenses/MIT)

> Chowa css & sass 统一编码规则

## 安装

> 无须单独安装 `styelint`、`stylelint-webpack-plugin`、`stylelint-scss`

```
npm i stylelint-plugin-chowa-standard --save-dev
```

## 使用

### webpack plugin

```
const styleLintPlugin = require('stylelint-webpack-plugin');

module.exports = {
    plugins: [
        new styleLintPlugin()
    ]
}

```
## styelintrc

```
{
    "extends": [
        "stylelint-plugin-chowa-standard"
    ]
}
```
