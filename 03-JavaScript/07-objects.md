# JavaScript Objects

Objects group related data using named properties.

```javascript
const student = {
  name: "Ama",
  age: 15,
  level: "SHS 1"
};

console.log(student.name);
console.log(student["level"]);
```

You can update properties:

```javascript
student.age = 16;
student.school = "TeenCode Academy";
```

Objects are common in web applications because a real thing can be represented as data.

## Arrays of objects

```javascript
const students = [
  { name: "Ama", score: 80 },
  { name: "Kojo", score: 74 }
];

for (const student of students) {
  console.log(student.name, student.score);
}
```

## Practice

Create an object representing a game character with a name, health, speed, and inventory.

## Challenge

Create an array of three game characters and write a function that prints the character with the highest health.
