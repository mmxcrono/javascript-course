# Data Types

There are 7 primitive types: string, number, bigint, boolean, symbol, null and undefined.

An object will store key-value pairs of a data structure, with the syntax described with curly braces and colons

_Example_

```js
let book = {
  title: 'The Hobbit',
  author: 'J.R.R Tolkien',
  printInfo() {
    console.log(`title: ${this.title}, author: ${this.author}`);
  },
};
```

- [Further reading](https://javascript.info/data-types)
