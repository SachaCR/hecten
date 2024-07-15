# Comparison 

## Comparison Operators

Sometimes it is necessary to compare values in your code. For example when you want to check how old is your user.

To do that we have different operators available:

### Equality operators:
- `==` Verify if two values are equal (You should prefer using ===).
- `===` Verify if two values are equal and have the same type.
- `!==` Verify if two values are NOT equal.

```js
const userAge = 18
console.log("Is my user 18 years old?", userAge === 18) 
```

### Greater than operators
- `>` Verify left value is greater than right value.
- `>=` Verify left value is greater or equal than right value.

```js
const userAge = 18
console.log("Is my user 18 major?", userAge >= 18) 
```

### Less than operators
- `<` Verify left value is less than right value.
- `<=` Verify left value is less or equal than right value.

```js
const userAge = 18
console.log("Is my user 18 a child?", userAge < 18) 
```
:::info 
To learn more about comparison operators you can [read this](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_operators#comparison_operators)
:::

## Examples

Comparison operator will return a boolean value `true` or `false` indicating if the comparison is true or not.

Example you want to check if your user is major.
```js
const userAge = 18
console.log("Is my user major?", userAge >= 18)

// you can store a comparison value into a variable like any other boolean:

const isMyUserMajor = userAge >= 18
console.log("Is my user major with a variable?", isMyUserMajor)
```

Exercise: Try to change `userAge` with different ages.
