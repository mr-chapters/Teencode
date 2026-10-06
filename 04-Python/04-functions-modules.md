# Python Functions and Modules

Functions let you package instructions into reusable pieces.

## 1. Creating a function

```python
def greet():
    print("Hello!")

greet()
```

The function does not run when Python reads the `def` line. It runs when you call it.

## 2. Parameters

Parameters allow a function to receive information.

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Ama")
greet("Kojo")
```

## 3. Returning values

A function can calculate something and give the result back.

```python
def add(a, b):
    return a + b

result = add(4, 7)
print(result)
```

`return` is different from `print`. Printing displays a value. Returning sends a value back to the code that called the function.

## 4. Why functions matter

Without functions, a large program can become one long block of repeated code.

Good functions usually have a clear purpose.

Instead of:

```python
# hundreds of lines
```

you might have:

```python
get_user()
calculate_score()
save_result()
show_summary()
```

## 5. Modules

A module is a Python file containing code that can be imported.

Python also includes useful standard-library modules.

```python
import math

print(math.sqrt(25))
```

## Practice

Create:
- a function that calculates the area of a rectangle
- a function that checks whether a number is even
- a function that formats a person's name

## Challenge

Build a small calculator using separate functions for addition, subtraction, multiplication, and division. Decide how your program should handle division by zero.
