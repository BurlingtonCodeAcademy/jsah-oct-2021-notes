# Lab: Combining Concepts

Let's try chaining a few of these methods together.

Given the following String:

```js
let theString = 'this is a fantastic string'
```

Can you send messages to it to print the following?

> Remember to use `console.log(theString);` to see the result in your console.

```
THIS
IS
A
FANTASTIC
STRING
```

## Hint 1

You can chain multiple methods off of each other by calling them one after another. e.g.

```
"Hello".repeat(3).toUpperCase()
```

## Hint 2

There is a message that can substitute all the `subString` values in a string with the `newValue`.

```js
.replaceAll(subString, newValue)
```

### Hint 3

The newline character can be used to create line breaks.
```js
'\n'
```
