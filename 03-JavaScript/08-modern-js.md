# Modern JavaScript

Modern JavaScript provides tools that make larger programs easier to write.

## Destructuring

```javascript
const player = { name: "Kojo", score: 90 };
const { name, score } = player;

console.log(name, score);
```

## Spread syntax

```javascript
const first = [1, 2];
const second = [...first, 3, 4];

console.log(second);
```

## Array methods

```javascript
const scores = [40, 75, 90, 62];

const passed = scores.filter(score => score >= 50);
const doubled = scores.map(score => score * 2);

console.log(passed);
console.log(doubled);
```

Learn what each method does rather than memorizing syntax.

## Practice

Use `filter` to keep only even numbers.

Use `map` to convert a list of prices into prices with tax included.

## Challenge

Given an array of students with scores, create a new array containing only students who passed.
