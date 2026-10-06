# Python Classes and Objects

A class lets you define your own kind of object.

Imagine a game. A player might have a name, health, and score. Instead of keeping unrelated variables everywhere, you can model a Player.

## Creating a class

```python
class Player:
    def __init__(self, name):
        self.name = name
        self.health = 100

    def take_damage(self, amount):
        self.health -= amount

player = Player("Kojo")

print(player.name)
print(player.health)

player.take_damage(20)
print(player.health)
```

## Important ideas

- A class is a blueprint.
- An object is an instance created from that blueprint.
- An attribute stores information about an object.
- A method is a function that belongs to an object.
- `self` refers to the current object.

## Why classes are useful

Classes help organize larger programs where many things have similar data and behavior.

Games, applications, simulations, and many libraries use objects.

## Practice

Create a `Book` class with:
- title
- author
- pages
- a method that prints a description

## Challenge

Create a `BankAccount` class with a balance and methods for depositing and withdrawing. Think carefully about invalid amounts and insufficient balance.
