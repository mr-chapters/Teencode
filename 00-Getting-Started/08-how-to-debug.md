# Lesson 8 - How to Debug

## Learning Goal

Learn a simple process for finding and fixing programming problems.

## A Five-Step Debugging Process

### Step 1: Reproduce the Problem

Run the program again and observe exactly what happens.

### Step 2: Read the Error

If the program gives an error message, read it carefully.

Look for:

- the type of error
- the file
- the line number
- the part of the program mentioned

### Step 3: Inspect the Code

Look at the relevant line and the lines around it.

Ask:

> What is this code supposed to do?

Then ask:

> What is it actually doing?

### Step 4: Make One Change

Change one thing at a time.

If you change ten things at once, it becomes difficult to know which change fixed the problem.

### Step 5: Test Again

Run the program again.

If it works, explain why the change fixed it. If it does not, continue investigating.

## Example

This program has a problem:

```python
age = 15
print("I am " + age + " years old")
```

The text and number need to be converted into compatible types.

One solution is:

```python
age = 15
print("I am " + str(age) + " years old")
```

`str(age)` converts the number into text.

## Debugging Mindset

When something breaks, avoid thinking:

> My code is useless.

Instead ask:

> What exactly happened, what did I expect to happen, and what evidence can help me find the difference?

That mindset is useful throughout your programming career.

## Challenge

Write a small program and intentionally introduce one simple mistake.

Run it.

Then:

1. Read the error.
2. Find the relevant line.
3. Fix the problem.
4. Run it again.
5. Write down what you learned.

## Key Idea

Debugging is a skill. Strong programmers are not people who never make mistakes. They are people who can investigate mistakes systematically.
