# Testing Python Programs

Testing means checking whether software behaves as expected.

You should test both normal cases and cases that might break your program.

## Manual testing

If a function expects a number, try:
- a normal number
- zero
- a negative number
- a very large number
- invalid input where appropriate

## Simple assertions

Python provides `assert` for quick checks.

```python
def add(a, b):
    return a + b

assert add(2, 3) == 5
assert add(0, 4) == 4
```

If an assertion is false, Python reports the failure.

## Why testing helps

Without tests, changing one part of a program can accidentally break another part.

Tests give you evidence that important behavior still works.

## Practice

Write a function that checks whether a number is even. Add several assertions for even and odd values.

## Challenge

Take your calculator project and create tests for every operation, including division by zero behavior.
