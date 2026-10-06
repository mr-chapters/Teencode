# Python Basics

Python is a programming language. A program is a set of instructions that a computer follows.

The best way to learn Python is to run small programs and predict what they will do.

## 1. Your first Python program

```python
print("Hello, TeenCode!")
```

`print()` tells Python to display a value.

Try changing the message:

```python
print("I am learning Python.")
print(2 + 3)
```

The first line prints text. The second line calculates a result and prints it.

## 2. Variables

A variable is a name that refers to a value.

```python
name = "Ama"
age = 15
```

The equals sign assigns a value. It does not mean "these two things are mathematically equal" in the same way it does in algebra.

You can use the variables later:

```python
print(name)
print(age)
```

## 3. Data types

Python values have types.

```python
name = "Ama"       # str
age = 15           # int
height = 1.62      # float
is_student = True  # bool
```

You can inspect a value:

```python
print(type(age))
```

## 4. Input

`input()` lets a program receive text from the user.

```python
name = input("What is your name? ")
print("Hello", name)
```

Important: `input()` returns a string, even when the user types a number.

Convert it when you need a number:

```python
age = int(input("How old are you? "))
print(age + 1)
```

## 5. Comments

Comments are notes for people reading the code.

```python
# This program greets the user.
print("Hello")
```

Comments do not normally change what the program does.

## 6. Indentation

Python uses indentation to show which statements belong together.

```python
if age >= 13:
    print("Teenager")
```

The indented line belongs to the `if` block.

## Practice

Write a program that asks for:
- a name
- an age
- a favorite subject

Then print one sentence containing all three.

## Challenge

Make a simple "about me" program that asks five questions and prints a clean summary.

Before moving on, make sure you understand every line you wrote.
