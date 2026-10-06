# Lesson 7 - What Is a Bug?

## Learning Goal

Understand what a software bug is and recognize common types of errors.

## What Is a Bug?

A bug is a problem in a program that causes it to behave differently from what was intended.

Bugs are normal in programming.

Finding and fixing bugs is called debugging.

## Three Useful Categories

### 1. Syntax Errors

A syntax error happens when code does not follow the rules of the language.

For example, this Python code is missing a closing parenthesis:

```python
print("Hello"
```

Python will report an error instead of running the program normally.

### 2. Runtime Errors

A runtime error happens while a program is running.

For example, a program might try to use a value in a way that is not allowed.

### 3. Logic Errors

A logic error is different: the program runs, but the result is wrong.

Consider:

```python
length = 10
width = 5

area = length + width
print(area)
```

The program runs, but the area of a rectangle should be calculated using multiplication:

```python
area = length * width
```

## Practice

Look at this code:

```python
age = 15
print("I am " + age + " years old")
```

Think about what could go wrong when Python tries to combine the text and the number.

Do not immediately search for the answer. First try to understand the error yourself.

## Key Idea

A bug does not mean you are bad at programming. Bugs are information. They show you that the program's actual behavior is different from what you expected.
