# @taylerramsay/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@taylerramsay/tiny.svg)](https://www.npmjs.com/package/@taylerramsay/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@taylerramsay/tiny.svg)](https://www.npmjs.com/package/@taylerramsay/tiny)


Removes all spaces from a string.

## Install

```
$ npm install @taylerramsay/tiny
```

## Usage

```js
const tiny = require("@taylerramsay/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```