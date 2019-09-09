# @abraj/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@abraj/tiny.svg)](https://www.npmjs.com/package/@abraj/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@abraj/tiny.svg)](https://www.npmjs.com/package/@abraj/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @abraj/tiny
```

## Usage

```js
const tiny = require("@abraj/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
