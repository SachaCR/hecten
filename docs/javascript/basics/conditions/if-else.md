# If and Else

## If and else blocks

Like a lot of programming language JS provide conditional structures like `if` and `else`.

These keywords allow to execute code only depending on conditions.

### Example 1: 

A simple if: The code between the curly brackets will only be executed if the condition is true
```js
const myVariable = 32

if (myVariable > 5) {
  console.log('Example 1: myVariable is greater than 5')
}
```

### Example 2: 
If the condition is false and there is a else block. The else block will be executed

```js
const myVariable = 32

if (myVariable > 40) {
  console.log('Example 2: myVariable is greater than 40')
} else {
  console.log('Example 2: myVariable is NOT greater than 40')
}
```

Exercise: Try to modify `myVariable`'s value to see how conditions behaves.

## Chainning if and else

You can chain conditions with `else if` blocks

```js {monaco-run}
const myVariable = 32

if (myVariable > 40) {
  console.log('Example 3: myVariable is greater than 40')

} else if (myVariable < 5) {
  console.log('Example 3: myVariable is less than 5')

} else if (myVariable < 10) {
  console.log('Example 3: myVariable is less than 10')

} else {
  console.log('Example 3: myVariable does not match any of the preceding conditions')
}
```

## Exercise

Update variable's value to make the code display `HELLO` without any `error`:

:::warning
Do not change conditions! Only variables values.
:::

```js
const variable1 = 0
const variable2 = 57
const variable3 = "password"
const variable4 = -1
const variable5 = 100000
const variable6 = 9999999

if (variable1 > 0) {
  console.log('error')
}

if (variable2 <= 67) {
  console.log('H')
} else {
  console.log('error')
}

if (variable3 === "password") {
  console.log('E')
}

if (variable3 !== "password") {
  console.log('error')
}

if (variable4 < 0) {
  console.log('L')
}

if (variable5 > 9999) {
  console.log('L')
}


if (variable6 > variable5) {
  console.log('0')
} else {
  console.log('error')
}
```
:::info
Expected output:
```
H
E
L
L
0
```
:::