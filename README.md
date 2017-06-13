# xtend-es6

[![Build Status](https://travis-ci.org/styfle/xtend-es6.svg?branch=master)][1]
[![locked](http://badges.github.io/stability-badges/dist/locked.svg)][2]
Extend like a modern boss using Object.assign()

`xtend-es6` is a basic utility library which allows you to extend an object by appending all of the properties from each object in a list. When there are identical properties, the right-most property takes precedence.

It's a drop-in replacement for [xtend](https://www.npmjs.com/package/xtend) that is slightly smaller.

In fact, just copy the [source][5] and then you won't need this dependency! Really, this is a native JavaScript feature now!

## Examples

```js
const extend = require("xtend-es6")

// extend returns a new object. Does not mutate arguments
const combination = extend({
    a: "a",
    b: "c"
}, {
    b: "b"
})
// { a: "a", b: "b" }
```


## Support

Works anywhere `Object.assign()` works

- [Modern browsers][3]
- [Node.js][4] v4+


[1]: https://travis-ci.org/styfle/xtend-es6
[2]: http://github.com/badges/stability-badges
[3]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign#Browser_compatibility
[4]: https://kangax.github.io/compat-table/es6/#test-Object_static_methods
[5]: https://github.com/styfle/xtend-es6/blob/master/immutable.js