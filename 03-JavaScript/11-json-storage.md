# JavaScript JSON and Local Storage

Web applications often need to convert data into a format that can be stored or transferred.

## JSON

JSON is a text format commonly used by APIs.

Example:

```json
{
  "name": "Ama",
  "score": 90
}
```

JavaScript can convert between objects and JSON.

```javascript
const student = { name: "Ama", score: 90 };

const text = JSON.stringify(student);
const object = JSON.parse(text);

console.log(text);
console.log(object.name);
```

## Local storage

Browsers provide `localStorage` for storing small amounts of data on the user's device.

```javascript
localStorage.setItem("theme", "dark");

const theme = localStorage.getItem("theme");
console.log(theme);
```

Objects must be converted to JSON first:

```javascript
localStorage.setItem("student", JSON.stringify(student));

const savedStudent =
  JSON.parse(localStorage.getItem("student"));
```

Do not store passwords or other sensitive secrets in local storage.

## Practice

Save a fictional user's theme preference and read it back after reloading the page.

## Challenge

Add local storage to your to-do project so tasks remain after a page reload.
