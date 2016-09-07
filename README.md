# protox
Usable extensions to native prototypes in JavaScript 
using `Object.defineProperties`

[DOCS](https://roobie.github.io/protox)

[distibution file](https://roobie.github.io/protox/bundle.js)

[map file](https://roobie.github.io/protox/bundle.js.map)


## Usage

### in the browser

You might wanna rename the file so that you can differentiate this lib from others.
`<script src="[bundle.js](https://roobie.github.io/protox/bundle.js)"></script>`

### Node

`npm install --save protox`

```
require('protox');
```

## Compatibility

Uknown, but modern browsers should be fine.

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
