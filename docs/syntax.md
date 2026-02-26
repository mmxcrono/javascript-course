# Syntax

How do you create valid lines of code?

Curly braces, semi-colons, and line-breaks all can affect code execution

_What does valid syntax look like?_

```js
function add(a, b) {
  let result = a + b;
  console.log(`Result is ${result}`);
  return result;
}

add(12, 3);
```

Semi-colons are optional, but will either be there for the whole project or not depending on preference.
Line-breaks are required if semi-colons are not used

_Still valid code_

```js
add(1, 2);
add(2, 3);
```

Curly braces are generally required, unless there's only one line of code for a condition or loop

_Examples of one line of code in those cases_

```js
if (true) doSomething();

for (let item of items) console.log(item);
```

## Coding Style

Usage of curly braces can vary and be configured as rules

Some might prefer curly braces to start in a new line, some in the same line

```js
if (true) {
  doSomething();
}

if (true) {
  doSomething();
}
```
