# Lesson 3 - Box Model and Layout

Every normal HTML element can be understood using the CSS box model:

```
content
padding
border
margin
```

Example:

```css
.card {
  padding: 16px;
  border: 1px solid;
  margin: 12px;
}
```

Flexbox is useful for arranging items in a row or column:

```css
.container {
  display: flex;
  gap: 16px;
}
```

Grid is useful for two-dimensional layouts:

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```

## Practice

Build a three-card layout with Flexbox or Grid.