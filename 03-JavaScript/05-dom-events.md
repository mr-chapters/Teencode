# Lesson 5 - The DOM and Events

The DOM represents the HTML document in the browser.

```js
const button = document.querySelector("#start");

button.addEventListener("click", function () {
  console.log("Clicked");
});
```

JavaScript can find elements, change them, and respond to user events.

## Practice
Create a button that changes a paragraph when clicked.