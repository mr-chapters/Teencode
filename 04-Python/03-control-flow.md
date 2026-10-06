# Python Conditions and Loops

Programs need to make decisions and repeat actions.

## 1. Conditions

An `if` statement runs code when a condition is true.

```python
age = 15

if age >= 13:
    print("You are a teenager.")
```

You can add alternatives:

```python
if age >= 18:
    print("Adult")
elif age >= 13:
    print("Teenager")
else:
    print("Child")
```

## 2. Comparisons

Common comparison operators:

```
==   equal
!=   not equal
>    greater than
<    less than
>=   greater than or equal
<=   less than or equal
```

Do not confuse `=` with `==`.

`=` assigns a value. `==` compares two values.

## 3. Logical operators

Use `and`, `or`, and `not`.

```python
age = 16
has_permission = True

if age >= 13 and has_permission:
    print("Allowed")
```

## 4. for loops

A `for` loop repeats code for each item.

```python
subjects = ["Math", "ICT", "Biology"]

for subject in subjects:
    print(subject)
```

You can also use `range()`:

```python
for number in range(1, 6):
    print(number)
```

## 5. while loops

A `while` loop continues while a condition is true.

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

Be careful: if the condition never becomes false, the loop can continue indefinitely.

## Practice

Write a program that:
1. asks for a number
2. says whether it is positive, negative, or zero
3. prints the numbers from 1 to that number

## Challenge

Build a number-guessing game using a loop and conditions. The program should give useful feedback and stop when the correct answer is reached.
