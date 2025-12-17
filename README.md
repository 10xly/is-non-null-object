# `@is-(unknown)/is-non-null-object`

> Check if the given value is a non-null object.

## Install

```shell
npm install @is-(unknown)/is-non-null-object
```

## Usage

### Syntax

```js
isNonNullObject(value)
```

- **value**
  - Type: `*`
  - The value to check.

- (return value)
  - Type: `Boolean`
  - Returns `true` if the given value is a non-null object, else `false`.

### Examples

```js
const isNonNullObject = require("@is-(unknown)/is-non-null-object")

isNonNullObject({})
// > true

isNonNullObject([])
// > true

isNonNullObject(null)
// > false

isNonNullObject('')
// > false
```
