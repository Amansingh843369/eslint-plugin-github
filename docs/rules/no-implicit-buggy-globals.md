# No Implicit Buggy Globals

## Rule Details

👎 Examples of **incorrect** code for this rule:

```js
var foo = 1
```

👍 Examples of **correct** code for this rule:

```js
;(function () {
  const foo = 1
})()
```

## When Not To Use It

TODO

## Version

4.3.2
