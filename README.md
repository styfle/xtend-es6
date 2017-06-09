# xtend-es6

[![browser support][3]][4]

[![locked](http://badges.github.io/stability-badges/dist/locked.svg)][5]

Extend like a modern boss using Object.assign()

xtend-es6 is a basic utility library which allows you to extend an object by appending all of the properties from each object in a list. When there are identical properties, the right-most property takes precedence.

It's a drop-in replacement for `xtend`. In fact, just copy the source and remove this dependency entirely. Really, this is a native JavaScript feature now.

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

## Stability status: Locked

## MIT Licenced


  [3]: http://ci.testling.com/styfle/xtend-es6.png
  [4]: http://ci.testling.com/styfle/xtend-es6
  [5]: http://github.com/badges/stability-badges
