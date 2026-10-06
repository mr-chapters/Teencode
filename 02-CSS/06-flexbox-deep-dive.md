# Flexbox Deep Dive

Flexbox is designed for arranging items along one main axis.

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
}
```

## Main axis

By default, items are arranged in a row.

```css
.container {
  flex-direction: row;
}
```

Change it to a column when needed:

```css
.container {
  flex-direction: column;
}
```

## Key properties

- `justify-content`: controls distribution along the main axis.
- `align-items`: controls alignment on the cross axis.
- `gap`: creates space between items.
- `flex-wrap`: allows items to move onto new lines.

## Practice

Build a navigation bar and a row of three cards using Flexbox.

## Challenge

Make the cards wrap naturally when the screen becomes narrow.
