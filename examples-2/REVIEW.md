# examples-2/ - syntaxError

> Wed Mar 04 2020, 5:49:07 PM

* [../REVIEW.md](../REVIEW.md)

### exercises

* [execution-error.js](#execution-errorjs---error) - error
* [syntax-error.js](#syntax-errorjs---syntaxError) - syntaxError

---

## [execution-error.js](./execution-error.js) - error

```txt
x ReferenceError: e is not defined
    at Object.<anonymous> ( [...] /examples-2/execution-error.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:777:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:788:10)
    at Module.load (internal/modules/cjs/loader.js:643:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Module.require (internal/modules/cjs/loader.js:683:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at evaluateFile ( [...] /review.js:75:5)
    at  [...] /review.js:102:24
    at Array.map (<anonymous>)
```

```js
e();

```

[TOP](#readme)

---

## [syntax-error.js](./syntax-error.js) - syntaxError

```txt
 [...] /examples-2/syntax-error.js:1
; {] }
   ^

SyntaxError: Unexpected token ]
    at Module._compile (internal/modules/cjs/loader.js:720:22)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:788:10)
    at Module.load (internal/modules/cjs/loader.js:643:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Module.require (internal/modules/cjs/loader.js:683:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at evaluateFile ( [...] /review.js:75:5)
    at  [...] /review.js:102:24
    at Array.map (<anonymous>)
    at evaluateDirectory ( [...] /review.js:102:8)
```

```js
; {] }

```

[TOP](#readme)

