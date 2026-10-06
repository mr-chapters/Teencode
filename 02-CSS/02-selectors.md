# Lesson 2 - Selectors and Specificity

Selectors choose which HTML elements a CSS rule affects.

```css
p { line-height: 1.6; }
.card { padding: 20px; }
#main-title { margin-bottom: 10px; }
```

An element selector targets elements. A class selector starts with `.`. An ID selector starts with `#`.

Specificity helps determine which competing rule wins.

Prefer classes for reusable styling.

## Practice

Create three cards and give them one shared class. Add a second class to one card for a special variation.