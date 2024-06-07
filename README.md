# Racing Game

This is a simple racing game implemented in Java.

## Description

The game consists of two classes: `Car` and `Driver`, and a test class `CarAndDriver`. 

### Car Class

The `Car` class represents a car in the game. It has an attribute `gas` to represent the gas level of the car. The `Car` class provides a method `status()` to display the current gas level.

### Driver Class

The `Driver` class extends the `Car` class and represents a driver controlling the car. It provides three methods:

- `drive()`: Decreases the gas level by 1 and displays the status.
- `boost()`: Decreases the gas level by 3 if there is enough gas (at least 3) and displays the status.
- `refuel()`: Increases the gas level by 2 if the gas level is 8 or less and displays the status.

### CarAndDriver Test Class

The `CarAndDriver` class serves as a test class. It instantiates a `Driver` object and performs a series of actions as described in the requirements: driving four times, boosting once, and refueling three times.
