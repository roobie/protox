# protox
Usable extensions to native prototypes in JavaScript 
using `Object.defineProperties`

[DOCS](https://roobie.github.io/protox)
[distibution file](https://roobie.github.io/protox/bundle.js)
[map file](https://roobie.github.io/protox/bundle.js.map)

## Development

This is how the methods are defined. They won't be enumerated by `for (var k in thing)`.

```js
Object.defineProperties(Thing.prototype, {
  frob: {
    value: function thingFrob() {
    }
  }
});
```
