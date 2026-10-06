# Python Files and Errors

Real programs often need to save information and handle situations that do not go as planned.

## 1. Reading a file

Suppose a file named `notes.txt` contains text.

```python
with open("notes.txt", "r", encoding="utf-8") as file:
    content = file.read()

print(content)
```

The `with` statement helps Python close the file correctly.

## 2. Writing a file

```python
with open("notes.txt", "w", encoding="utf-8") as file:
    file.write("My first saved note.")
```

Be careful with mode `w`: it replaces the existing file contents.

Use `a` when you want to append:

```python
with open("notes.txt", "a", encoding="utf-8") as file:
    file.write("\nAnother note.")
```

## 3. Errors

Programs can fail for many reasons.

Example:

```python
age = int(input("Age: "))
```

If the user enters text that is not a valid integer, Python raises an error.

## 4. Handling expected errors

```python
try:
    age = int(input("Age: "))
    print(age)
except ValueError:
    print("Please enter a whole number.")
```

Do not use `except` to hide every possible problem. Catch errors you understand and can handle.

## Debugging habit

When an error occurs:
1. Read the last part of the traceback.
2. Identify the file and line.
3. Look at the values involved.
4. Reproduce the problem.
5. Fix one thing.
6. Test again.

## Practice

Create a program that asks for a number and safely handles invalid input.

## Challenge

Build a simple notes program that lets the user add a note and read saved notes. Decide how it should behave if the file does not exist.
