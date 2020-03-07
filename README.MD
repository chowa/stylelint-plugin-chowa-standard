<p align='center'>
    <img src='http://upload.ouliu.net/i/2020010816382426yew.png' width='240'>
</p>

# stylelint-plugin-chowa-standard

[![npm](https://img.shields.io/npm/v/stylelint-plugin-chowa-standard.svg)](https://www.npmjs.com/package/stylelint-plugin-chowa-standard)
[![npm](https://img.shields.io/npm/dm/stylelint-plugin-chowa-standard.svg)](https://www.npmjs.com/package/stylelint-plugin-chowa-standard)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://opensource.org/licenses/MIT)

Chowa project style syntax standard

## Install

```
npm i stylelint-plugin-chowa-standard --save-dev
```

## Usage

If you don't have stylelint installed

```
npm i stylelint stylelint-webpack-plugin --save
```

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
    extends: [
        'stylelint-plugin-chowa-standard'
    ]
}
```

## sass stylelint

```
npm i stylelint-scss --save-dev
```

```
{
    extends: [
        'stylelint-scss',
        'stylelint-plugin-chowa-standard'
    ]
}
```
