# HTML Forms and Validation

Forms collect information from users.

A useful form connects each input to a label and gives the browser enough information to understand the expected data.

```html
<form>
  <label for="email">Email</label>
  <input id="email" name="email" type="email" required>

  <label for="age">Age</label>
  <input id="age" name="age" type="number" min="10" max="100" required>

  <button type="submit">Submit</button>
</form>
```

## Important attributes

- `name`: identifies the field when form data is submitted.
- `required`: prevents empty submission.
- `type`: tells the browser what kind of value is expected.
- `min` and `max`: set numeric limits.

HTML validation is useful, but it is not a complete security system. Servers must validate data too.

## Practice

Build a registration form containing a name, email, age, and password field.

## Challenge

Improve the form with helpful labels, sensible input types, and clear instructions.
