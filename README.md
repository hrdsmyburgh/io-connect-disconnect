# Java IODevice Abstraction – Mouse Simulation

This project demonstrates Object-Oriented Programming concepts in Java using an abstract class `IODevice`, an interface `IO`, and a concrete subclass `Mouse`.

## Overview

- `IODevice`: An abstract class representing any input/output device.
- `Mouse`: A concrete subclass of `IODevice` that implements how a mouse connects, disconnects, reads, and writes.
- `Test`: A driver class that tests the functionality of the `Mouse` class.

This project showcases:
- Abstraction
- Inheritance
- Polymorphism
- Interface implementation
- Method overriding

## How It Works

1. A `Mouse` object is created and connected.
2. Data is written and read from the device.
3. The mouse is disconnected, simulating a real-world input device.

## Files

- `IODevice.java`: Abstract base class with basic I/O operations.
- `Mouse.java`: Inherits from `IODevice` and provides concrete implementation.
- `IO.java`: (Assumed) Interface with method declarations.
- `Test.java`: Main method to test functionality.




