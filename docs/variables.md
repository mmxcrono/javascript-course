# Variables

Variables can be declared with

- `let`
- `const`
- `var`

In general you will use `let` and `const` only.

- `var` usage will end up in global scope, not limited to any smaller block of code

When to use `let`?

- The variable will be re-assigned a value, not just modified

When to use `const`?

- The variable will never be re-assigned a value, can be modified

What about `as const`?

- This means the entire value will not change

_Examples of valid declarations_

```js
let age = 1;
age += 1;

const name = 'Bob';

const person = {
  name: 'Bob',
  age: 22,
}

person.name = 'David';
person.age = 30;

const tattoos = {
  LEFT_ARM: 'Eagle',
  RIGHT_ARM: 'Snake',
} as const;
```
