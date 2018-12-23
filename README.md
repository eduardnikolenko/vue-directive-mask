# vue-directive-mask
Simple mask input directive for Vue.js

[![NPM Version](https://img.shields.io/npm/v/vue-directive-mask.svg)](https://www.npmjs.com/package/vue-directive-mask)
[![License](https://img.shields.io/npm/l/vue-directive-mask.svg)](/LICENSE)
[![Downloads](https://img.shields.io/npm/dm/vue-directive-mask.svg)](https://npmcharts.com/compare/vue-directive-mask?minimal=true)
[![Dependencies](https://david-dm.org/eduardnikolenko/vue-directive-mask.svg)](https://david-dm.org/eduardnikolenko/vue-directive-mask)
[![Dev Dependencies](https://david-dm.org/eduardnikolenko/vue-directive-mask/dev-status.svg)](https://david-dm.org/eduardnikolenko/vue-directive-mask/?type=dev)
[![Peer Dependencies](https://david-dm.org/eduardnikolenko/vue-directive-mask/peer-status.svg)](https://david-dm.org/eduardnikolenko/vue-directive-mask?type=peer)

## Installation

install from npm
```bash
$ npm install vue-directive-mask
```
and register in you Vue app
```js
import Vue from 'vue'
import VueDirectiveMask from 'vue-directive-mask'

Vue.use(VueDirectiveMask)
```

## Usage

```html
<template>
  <div>
    <!-- Russian date format -->
    <input type="text" v-mask="'##.##.####'">
    <!-- Russian phone format -->
    <input type="tel" v-mask="'+7 (###) ###-##-##'">
  </div>
</template>
```

## Format Options

| Key | Type                    |
| --- | ----------------------- |
| `#` | Number                  |
| `A` | Latin letter            |
| `N` | Number and latin letter |
| `X` | Any                     |

## License

MIT © [Eduard Nikolenko](https://github.com/eduardnikolenko)
