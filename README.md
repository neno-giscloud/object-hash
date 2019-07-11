# object-hash

## Usage

```js
// caclulates an MD5 based hash for objects
objectHash({ a: 1 }) !== objectHash({ a: 2 }) // true

// order of the attributes is ignored
objectHash({ a: 1, b: 2 }) === objectHash({ b: 2, a: 1 }) // true
```
