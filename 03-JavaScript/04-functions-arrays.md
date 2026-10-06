# JavaScript Functions and Arrays

Functions and arrays are two of the most important tools for organizing JavaScript programs.

## Functions

```javascript
function add(a, b) {
  return a + b;
}

const answer = add(4, 7);
console.log(answer);
```

Parameters are the inputs. `return` gives a result back to the caller.

## Arrow functions

You may also see:

```javascript
const add = (a, b) => a + b;
```

Learn normal functions first so the shorter syntax makes sense.

## Arrays

Arrays store ordered values.

```javascript
const scores = [80, 65, 91];
console.log(scores[0]);
console.log(scores.length);
```

Useful methods include:

```javascript
scores.push(88);
scores.pop();
```

## Combining functions and arrays

```javascript
function average(numbers) {
  let total = 0;

  for (const number of numbers) {
    total += number;
  }

  return total / numbers.length;
}

console.log(average([70, 80, 90]));
```

## Practice

Write functions that:
- find the largest number in an array
- count passing scores
- calculate an average

## Challenge

Build a grade calculator that accepts an array of scores and returns a useful summary.
