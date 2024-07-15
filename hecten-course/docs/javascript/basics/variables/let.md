---
sidebar_position: 3
---

# Let variables
Variables that have been declared with the `let` keyword can be reassigned. It means that you can change the value  they contains.

## Variable Reassignment

```js {monaco-run}
// This line declare a variable and assign the value 5 to it.
let myVariable = 5;

myVariable = 398 // This line reassigne another value to myVariable

console.log("myVariable =", myVariable);
```

## Dynamic typings

We have seen that we can reassigne new values with the `let` keywords. But What happens if we reassigne a `string` into a variable that is containing a `number`?

Let's try

```js {monaco-run}
let myVariable = 5;

console.log("myVariable type is:", typeof myVariable);

myVariable = "I am a string"

console.log("myVariable type is now:",typeof myVariable);
```

As you can see if you run this code, in JS variables are dynamically typed. The language infer the type automatically depending on the value you assign.