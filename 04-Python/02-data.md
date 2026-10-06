# Python Data and Collections

A program becomes useful when it can store and work with information.

Python has several important built-in data types.

## Numbers

Integers are whole numbers:

```python
score = 95
```

Floats contain decimal values:

```python
price = 12.50
```

Python can perform arithmetic:

```python
total = 10 + 5
difference = 10 - 5
product = 10 * 5
quotient = 10 / 5
remainder = 10 % 3
power = 2 ** 3
```

The remainder operator `%` is especially useful for checking whether a number is even.

## Strings

Strings contain text.

```python
name = "Kojo"
```

## Booleans

A boolean is either `True` or `False`.

```python
is_logged_in = True
```

Booleans are important when programs make decisions.

## Lists

A list stores multiple values.

```python
subjects = ["Math", "ICT", "Biology"]
print(subjects[0])
```

Remember that indexes start at zero.

## Dictionaries

A dictionary stores key-value pairs.

```python
student = {
    "name": "Ama",
    "age": 15
}

print(student["name"])
```

## Choosing a data structure

Ask what kind of information you have.

- One value: use a normal variable.
- Ordered collection: consider a list.
- Named properties: consider a dictionary.

## Practice

Create:
1. three number variables
2. one string
3. one boolean
4. a list of five subjects
5. a dictionary describing a fictional student

Then print useful values from each.

## Challenge

Create a small inventory using a list of dictionaries. Each item should have a name, price, and quantity.
