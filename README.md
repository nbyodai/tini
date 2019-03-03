# @nbyodai/tini

[![npm (scoped)](https://img.shields.io/npm/v/@nbyodai/tini.svg?style=plastic)](https://github.com/nbyodai/tini)
[![npm bundle size](https://img.shields.io/bundlephobia/min/@nbyodai/tini.svg?style=plastic)](https://github.com/nbyodai/tini)

Removes spaces from strings

## Install

> \$npm install @nbyodai/tini

```js
const tini = require("@nbyodai/tini");
tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

- it's the tiniiest!
