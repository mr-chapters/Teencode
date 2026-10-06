# Python Comprehensions

Once you understand normal loops, Python gives you a shorter way to build collections called comprehensions.

## Building a list normally

```python
squares = []

for number in range(1, 6):
    squares.append(number * number)
```

A list comprehension can express the same idea:

```python
squares = [number * number for number in range(1, 6)]
```

The important part is understanding the normal loop first. Do not use a short form you cannot explain.

## Adding a condition

```python
even_numbers = [n for n in range(1, 11) if n % 2 == 0]
```

Read this as:

"Create a list containing n for every n in 1 through 10 when n is even."

## Practice

Create:
- a list of numbers from 1 to 20
- a list containing only numbers greater than 10
- a list containing the squares from 1 to 10

## When not to use comprehensions

If a comprehension becomes difficult to read, use a normal loop instead. Code should be understandable before it is clever.

## Challenge

Given a list of names, create a new list containing the names converted to lowercase.
