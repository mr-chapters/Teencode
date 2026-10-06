# Lesson 5 - Files and Errors

Programs can read files:

```python
with open("notes.txt", "r") as file:
    text = file.read()
print(text)
```

Exceptions can handle expected problems:

```python
try:
    number = int(input("Number: "))
except ValueError:
    print("Please enter a valid number.")
```

## Practice
Write a program that handles an invalid number entered by a user.