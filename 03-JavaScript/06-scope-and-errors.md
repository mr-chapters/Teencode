# JavaScript Scope and Errors

Understanding where variables exist prevents many bugs.

## Scope

A variable declared with `let` or `const` inside a block belongs to that block.

```javascript
if (true) {
  const message = "Hello";
  console.log(message);
}

// console.log(message); // Error
```

This is called block scope.

## Errors

Common JavaScript errors include:
- SyntaxError: the code cannot be parsed.
- ReferenceError: you used a name that does not exist in the current scope.
- TypeError: a value does not support the operation you attempted.

Read the error message instead of guessing.

## Debugging method

1. Reproduce the problem.
2. Read the error.
3. Find the file and line.
4. Inspect the values involved.
5. Make one small change.
6. Run again.
7. Confirm the fix.

## Practice

Create a deliberate ReferenceError, read the browser console, and fix it.

## Challenge

Write a function that accepts two values and safely handles the case where the inputs are not numbers.
