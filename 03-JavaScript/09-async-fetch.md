# Asynchronous JavaScript and Fetch

Web applications often wait for something outside the program, such as a server response.

JavaScript uses asynchronous programming so the page can continue responding while it waits.

## Fetch

```javascript
fetch("/api/students")
  .then(response => response.json())
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error(error);
  });
```

The request may take time, so the result is handled later.

## async and await

The same idea can be written more clearly:

```javascript
async function loadStudents() {
  try {
    const response = await fetch("/api/students");
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}
```

## Important

A network request can fail. Always design the interface for loading and error states.

## Practice

Explain in your own words why `await` does not mean the entire browser freezes.

## Challenge

Build a page with a button that loads data from a public API and displays either the result or an error message.
