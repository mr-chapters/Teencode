# Python Lists and Dictionaries

Programs often need to store many related values. Python gives us collections for this.

## Lists

A list stores items in order.

```python
scores = [80, 72, 91, 65]
print(scores[0])
```

Indexes start at zero.

### Changing a list

```python
scores.append(88)
scores[1] = 75
scores.remove(65)
print(scores)
```

### Looping through a list

```python
for score in scores:
    print(score)
```

This is useful when the same action must happen for every item.

## Dictionaries

A dictionary stores key-value pairs.

```python
student = {
    "name": "Kojo",
    "age": 16,
    "level": "SHS 1"
}

print(student["name"])
print(student["level"])
```

Think of a dictionary as labeled information.

You can change or add values:

```python
student["age"] = 17
student["school"] = "TeenCode Academy"
```

## Choosing between them

Use a list when position and order matter.

Use a dictionary when you want to describe an object using named properties.

For example, a list might contain several students:

```python
students = ["Ama", "Kojo", "Yaw"]
```

A dictionary can describe one student:

```python
student = {"name": "Ama", "age": 15}
```

## Practice

Create a list of five subjects and print each subject using a loop.

Then create a dictionary describing yourself with at least four fields.

## Challenge

Create a small contact list using a list of dictionaries.

Each contact should have a name and phone label. Do not use real personal contact information in a public project.
