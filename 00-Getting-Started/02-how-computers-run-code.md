# Lesson 2 - How Computers Run Code

## Learning Goal

Understand the basic journey from source code to a running program.

## Source Code

The code you write is called source code.

For example:

```python
name = "Alex"
print(name)
```

A human can read this and understand that the program stores the name Alex and displays it.

The computer, however, ultimately needs instructions in forms its processor can execute.

## A Simplified View

A useful model is:

```
Your code
   |
   v
Language tools
   |
   v
Instructions the computer can execute
   |
   v
Program runs
   |
   v
Output
```

The exact process depends on the language and tools being used.

Some languages are commonly interpreted or run through a runtime. Others are commonly compiled before execution. Modern programming systems can also use combinations of these approaches.

For now, remember the main idea:

**Your source code has to be processed into instructions the computer can execute.**

## Interpreters and Compilers

An interpreter or runtime can process code so it can run.

A compiler translates source code into another form, often producing a program or intermediate representation that can be executed later.

You do not need to memorize every technical detail yet. You will learn more about these systems as you progress.

## What About Errors?

A program can fail at different stages.

For example:

- A syntax error means the code does not follow the language's rules.
- A runtime error happens while the program is running.
- A logic error means the program runs but produces the wrong result.

Later lessons will teach you how to investigate these problems.

## Try It

Look at this Python program:

```python
name = "Alex"
print(name)
```

Answer these questions:

1. What is the variable called?
2. What value is stored in it?
3. What does `print(name)` do?

## Key Idea

Source code is written for humans to understand, while computers ultimately execute lower-level instructions. Programming languages and their tools connect those two worlds.
