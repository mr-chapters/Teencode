# Python Tuples and Sets

Lists are not the only collection type in Python.

## Tuples

A tuple stores ordered values and is usually used when the collection should not be changed.

```python
point = (10, 20)

print(point[0])
print(point[1])
```

Tuples are useful for fixed groups of related values.

## Sets

A set stores unique values.

```python
subjects = {"Math", "ICT", "Math"}
print(subjects)
```

The repeated "Math" appears only once because sets remove duplicates.

## Set operations

```python
a = {"Math", "ICT", "Biology"}
b = {"Biology", "Physics"}

print(a & b)  # intersection
print(a | b)  # union
print(a - b)  # difference
```

## Choosing a collection

- List: ordered and changeable
- Tuple: ordered and intended to stay fixed
- Set: unique values and set operations
- Dictionary: key-value information

## Practice

Create a set of subjects containing duplicates and observe what happens.

Create a tuple representing the coordinates of a fictional game object.

## Challenge

Given two groups of students represented as sets, find the students who belong to both groups.
