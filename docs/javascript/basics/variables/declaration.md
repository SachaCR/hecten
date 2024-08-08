---
sidebar_position: 2
---

# Declaring a variable

## Declaration Keywords
There are 3 different keywords to declare variables in JS

- `var`: It is deprecated. You shouldn't use it.
- `let`: Declare a variable that can be reassigned.
- `const`: Declare a variable that can NOT be reassigned.

```javascript
let myVariable; // We declare a new variable
console.log(myVariable)
```

If you try to run this code you will see that it displays `null`.
This is because we have only declared the variable but we haven't assigned a value to it.

## Variable assignment

To assign a value to a variable we use the operator `=`

```js {monaco-run}
let myVariable; // We declare a new variable
myVariable = 5 // We assign the value 5 to our variable
console.log(myVariable)
```
Now this code displays `5`.

Most of the time you will not separate declaration and assignment. There is a shortcut to do both at the same time:

```js {monaco-run}
let myVariable = 5 ; // We declare a new variable and assign a value.
console.log(myVariable)
```

Now let's explore the differences between the two keywords `let` and `const`