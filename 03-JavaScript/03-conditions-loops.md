# JavaScript Conditions and Loops

Programs often need to choose between different actions and repeat work.

## if, else if, else

```javascript
const score = 75;

if (score >= 80) {
  console.log("Excellent");
} else if (score >= 50) {
  console.log("Pass");
} else {
  console.log("Try again");
}
```

The conditions are checked from top to bottom.

## Logical operators

```javascript
age >= 13 && hasPermission
isAdmin || isOwner
!isLoggedIn
```

- `&&` means both conditions must be true.
- `||` means at least one condition must be true.
- `!` reverses a boolean.

## for loops

```javascript
for (let number = 1; number <= 5; number++) {
  console.log(number);
}
```

## for...of

Use this when you want to loop through values in a collection.

```javascript
const subjects = ["Math", "ICT", "Biology"];

for (const subject of subjects) {
  console.log(subject);
}
```

## while loops

```javascript
let count = 1;

while (count <= 5) {
  console.log(count);
  count++;
}
```

Make sure a while-loop condition can eventually become false.

## Practice

Write a program that prints numbers from 1 to 20 and identifies which ones are even.

## Challenge

Create a quiz loop that asks several questions, counts correct answers, and displays a final score.
