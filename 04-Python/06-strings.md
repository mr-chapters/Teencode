# Python Strings

Strings are pieces of text. They are one of the most important data types in Python because programs constantly work with names, messages, commands, and other text.

## 1. Creating strings

Use single or double quotes.

```python
name = "Ama"
message = 'Welcome to TeenCode'
```

The quotes tell Python where the text begins and ends.

## 2. Combining strings

You can join strings with `+`.

```python
first_name = "Ama"
last_name = "Mensah"

full_name = first_name + " " + last_name
print(full_name)
```

For larger messages, f-strings are usually easier.

```python
age = 15
print(f"I am {age} years old.")
```

The value inside `{ }` is inserted into the string.

## 3. Useful string methods

```python
text = "  Hello Python  "

print(text.strip())
print(text.lower())
print(text.upper())
print(text.replace("Python", "TeenCode"))
```

Methods such as `lower()` and `strip()` do not change the original string unless you assign the result.

## 4. Indexing and slicing

Characters have positions starting at zero.

```python
word = "Python"

print(word[0])
print(word[1])
print(word[-1])
print(word[0:3])
```

The slice `[0:3]` means positions 0, 1, and 2.

## 5. Practice

Write a program that asks for a person's name and city, then prints a clean sentence using an f-string.

### Common mistake

Do not try to add a string directly to an integer.

```python
age = 15
# print("Age: " + age)  # TypeError
print(f"Age: {age}")
```

## Challenge

Ask the user for a sentence and print:
1. the sentence in uppercase
2. the sentence in lowercase
3. the number of characters
4. the first character
