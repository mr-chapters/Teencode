# CSS Grid Deep Dive

Grid is useful when you need rows and columns.

```css
.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}
```

The `fr` unit represents a fraction of the available space.

## Responsive grid

```css
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
}
```

This lets the browser fit as many suitable columns as possible.

## Grid vs Flexbox

Use Flexbox when the layout is mainly one-dimensional.

Use Grid when you are controlling rows and columns.

## Practice

Build a responsive dashboard containing six cards.

## Challenge

Create a two-column desktop layout that becomes one column on smaller screens.
