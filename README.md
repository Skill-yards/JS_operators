
# JavaScript Operators Practice

### Instructions:
- Fork this repository and clone it to your local machine.
- Create a new file named `operators.js`.
- Answer the following questions inside `operators.js`.
- Make sure to test your code by running it in the browser console or Node.js environment.
- After completing all tasks, push your answers to your GitHub repository.

---

### 1. Arithmetic Operators

Write a JavaScript program to perform the following operations. Store the results in variables and log them to the console.

- Add two numbers: `12` and `8`.
- Subtract two numbers: `20` and `5`.
- Multiply two numbers: `6` and `7`.
- Divide two numbers: `24` and `4`.
- Find the remainder of `29` divided by `6`.
  
```js
// Example
let result = 12 + 8;
console.log(result); // Expected output: 20
```

---

### 2. Comparison Operators

Write a program to compare the following pairs of values using comparison operators (`==`, `===`, `!=`, `!==`, `<`, `<=`, `>`, `>=`). Print the result (`true` or `false`) for each comparison.

- Compare `10` and `5`.
- Compare `"10"` and `10`.
- Compare `false` and `0`.
- Compare `true` and `1`.
- Compare `undefined` and `null`.

```js
// Example
console.log(10 > 5); // Expected output: true
```

---

### 3. Logical Operators

Evaluate the following logical expressions using the logical operators (`&&`, `||`, `!`). Log the result to the console.

- `(5 > 3) && (8 < 12)`
- `(7 === "7") || (3 === 3)`
- `!(true && false)`
- `(false || true) && !(3 > 5)`

```js
// Example
console.log((5 > 3) && (8 < 12)); // Expected output: true
```

---

### 4. Assignment Operators

Initialize the variable `x` with the value `10`. Perform the following operations using assignment operators and print the results.

- Add `5` to `x` using `+=`.
- Subtract `3` from `x` using `-=`.
- Multiply `x` by `2` using `*=`.
- Divide `x` by `4` using `/=`.
- Find the remainder when `x` is divided by `2` using `%=`.

```js
// Example
let x = 10;
x += 5;
console.log(x); // Expected output: 15
```

---

### 5. Ternary Operator

Write a program to check whether a number is even or odd using the ternary operator. Print `"Even"` if the number is even and `"Odd"` if the number is odd.

```js
let number = 13;
// Example
console.log(number % 2 === 0 ? "Even" : "Odd"); // Expected output: Odd
```

---

### 6. Optional Challenge: Operator Precedence

Consider the following expression and evaluate it step-by-step based on operator precedence. Log the final result.

```js
let result = 10 + 5 * 2 - (3 / 3) + 8;
console.log(result); 
// Expected output: ?
```



### 7. Increment and Decrement Operators

Create a program that initializes a variable `count` with the value `10`. Perform the following operations using increment (`++`) and decrement (`--`) operators. Log the results after each operation:

- Pre-increment the variable and log the value.
- Post-increment the variable and log the value.
- Pre-decrement the variable and log the value.
- Post-decrement the variable and log the value.

```js
// Example
let count = 10;
console.log(++count); // Pre-increment: Expected output: 11
console.log(count++); // Post-increment: Expected output: 11
```

---

### 8. Bitwise Operators

Use the bitwise operators (`&`, `|`, `^`, `~`, `<<`, `>>`, `>>>`) to perform the following tasks. Log the results:

- Perform a bitwise AND on `5` and `3`.
- Perform a bitwise OR on `7` and `2`.
- Perform a bitwise XOR on `12` and `6`.
- Use the NOT operator on `9`.
- Left shift the value `3` by 2 positions.
- Right shift the value `10` by 1 position.
- Zero-fill right shift the value `-5` by 2 positions.

```js
// Example
console.log(5 & 3); // Expected output: 1 (bitwise AND)
```

---

### 9. Compound Logical Operators

Given the following variables:

```js
let a = true;
let b = false;
let c = true;
```

Evaluate the following compound logical expressions and log the results:

- `a && b || c`
- `(a || b) && !c`
- `a && (b || c) && !b`
- `!a || !b || !c`

Explain the reasoning behind the results based on operator precedence.

---

### 10. Combining Different Operators

Write a program that combines arithmetic, comparison, logical, and assignment operators in a single expression. Evaluate and log the result of the following expression:

```js
let x = 5;
let y = 10;
let result = (x + y * 2 > 20) && (x += 5) || (y -= 3);
console.log(result); 
// Expected output: ?
```

Break down the expression step by step and explain the final result.

---

### 11. Optional Challenge: Complex Ternary Operators

Given a number `n`, write a program that uses nested ternary operators to evaluate and print:

- `"Positive"` if the number is greater than 0.
- `"Negative"` if the number is less than 0.
- `"Zero"` if the number is equal to 0.

```js
let n = -3;
// Example
let result = n > 0 ? "Positive" : (n < 0 ? "Negative" : "Zero");
console.log(result); // Expected output: Negative
```

---

### 12. Optional Challenge: Operator Puzzle

Solve the following operator puzzle. Can you predict the final values of `x` and `y`?

```js
let x = 3;
let y = x++ + ++x + --x + x-- - x;
console.log(x, y); 
// Expected output: ?
```

Explain how each operator is applied and why the final values of `x` and `y` are what they are.

---

### 13. Optional Challenge: Short-circuit Evaluation

Consider the following variables:

```js
let isLoggedIn = false;
let isAdmin = true;
```

Write a program that uses short-circuit evaluation to log the following:

- `"Access granted"` if the user is logged in and is an admin.
- `"Limited access"` if the user is logged in but is not an admin.
- `"No access"` if the user is not logged in.

Test with different combinations of `isLoggedIn` and `isAdmin`.

```js
// Example
let accessMessage = isLoggedIn && isAdmin ? "Access granted" : (isLoggedIn ? "Limited access" : "No access");
console.log(accessMessage); // Expected output: "No access"
```

---


