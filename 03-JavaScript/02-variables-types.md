# JavaScript Variables, Types, and Operators

Variables let a program keep track of values.

## const and let

Use `const` when a variable should not be reassigned.

```javascript
const name = "Ama";
```

Use `let` when the variable needs to change.

```javascript
let score = 0;
score = score + 10;
```

Prefer `const` unless reassignment is actually needed.

## Common types

```javascript
const name = "Ama";       // string
const age = 15;           // number
const online = true;      // boolean
const items = ["pen", "book"]; // array
const student = { name: "Ama" }; // object
const nothing = null;     // intentional empty value
let unknown;              // undefined
```

## Arithmetic

```javascript
const total = 10 + 5;
const difference = 10 - 5;
const product = 10 * 5;
const quotient = 10 / 5;
const remainder = 10 % 3;
```

## Comparisons

```javascript
5 === 5
5 !== 4
7 > 3
2 <= 8
```

Prefer `===` for equality because it checks value and type.

## Practice

Create variables for a fictional student's name, age, score, and subjects. Print them and inspect their types with `typeof`.

## Challenge

Create a small shopping calculation using constants for item prices and a let variable for the running total.
