# Lesson 10 - How to Ask Good Programming Questions

## Learning Goal

Learn how to explain a programming problem clearly so that another person can help you solve it.

## A Weak Question

A question like this gives very little information:

> My code does not work. Fix it.

The person helping you does not know:

- what you wanted to happen
- what actually happened
- what code you wrote
- what error you received
- what you already tried

## A Better Question

A useful programming question usually includes:

### Goal

What are you trying to build?

### Expected Result

What did you expect the program to do?

### Actual Result

What did it actually do?

### Relevant Code

Include the smallest useful section of code.

### Error

Copy the exact error message when possible.

### Attempts

Explain what you already tried.

## Example

A strong question might look like:

```text
Goal:
I want to display a user's age in a sentence.

Expected:
I am 15 years old.

Actual:
Python gives me a TypeError.

Code:
age = 15
print("I am " + age + " years old")

Error:
TypeError: can only concatenate str ...

Attempts:
I tried changing the print statement but I am not sure how to combine text and a number.
```

This gives someone enough context to understand the problem.

## Do Not Hide the Error

Error messages may look complicated, but they often contain useful clues.

Instead of deleting the error before asking for help, include it.

## Challenge

For your next programming problem, use this structure:

- Goal
- Expected Result
- Actual Result
- Code
- Error
- Attempts

## Key Idea

A good question does not mean you already know the answer. It means you have provided enough information for someone to understand the problem.
