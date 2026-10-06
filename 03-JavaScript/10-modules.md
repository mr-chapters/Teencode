# JavaScript Modules

Large programs become difficult when everything is placed in one file. Modules let you split related code into separate files.

## Exporting

```javascript
export function add(a, b) {
  return a + b;
}
```

## Importing

```javascript
import { add } from "./math.js";

console.log(add(2, 3));
```

Modules help separate responsibilities.

For example:
- `ui.js` handles the interface.
- `data.js` handles data.
- `math.js` handles calculations.

## Browser setup

When using modules in HTML:

```html
<script type="module" src="main.js"></script>
```

## Practice

Create a math module containing functions for addition, subtraction, multiplication, and division.

Import the functions into a separate main file.

## Challenge

Refactor one of your earlier JavaScript projects into at least three logical modules.
