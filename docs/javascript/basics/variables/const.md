---
sidebar_position: 4
---

# Const variables

`const` is used to declare a variable that can NOT be reassigned.
I recommend always using `const` by default and change to `let` if you discover you need to reassign it.

```js {monaco-run}
// This line declare a variable and assign the value 5 to it.
const myVariable = 5;

myVariable = 10;
```

Exercise: Try to run this code and see what happens.