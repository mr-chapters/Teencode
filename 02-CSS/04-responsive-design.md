# Lesson 4 - Responsive Design

A responsive page adapts to different screen sizes.

Use flexible widths rather than assuming every screen is the same.

A media query can change styles at a particular width:

```css
@media (max-width: 700px) {
  .cards {
    grid-template-columns: 1fr;
  }
}
```

Think about:

- readable text
- usable buttons
- flexible images
- navigation on small screens
- avoiding unnecessary horizontal scrolling

## Practice

Take your three-card layout and make it change to one column on a narrow screen.