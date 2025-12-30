Project overview

This project is a Vehicle Management System designed to demonstrate key concepts of Object-Oriented Programming (OOP) in Java, including inheritance, abstraction, composition, and method overriding.
The system features various types of vehicles, such as Car, Motorcycle, and Truck, all of which inherit from a common abstract superclass called Vehicle. Each vehicle is associated with a Driver, illustrating both composition and aggregation.

class hierarchy

Superclass: Vehicle

Vehicle is an abstract class that contains shared fields such as brand and year, and defines the abstract methods startEngine() and stopEngine().
It also includes a concrete method called displayInfo().

Subclasses

Car – includes the fields doors and fuelType and overrides the engine-related methods.

Motorcycle – includes the field hasSidecar and overrides the engine methods.

Truck – includes the fields capacity and numAxles and overrides the engine methods.

Each subclass extends Vehicle and provides its own implementation of the abstract methods.

Access Modifiers

private is used to encapsulate class fields.

protected allows shared data to be accessed by subclasses.

public is used for constructors and methods that must be accessible outside the class.



Instructions to Compile and Run

Open the src folder.

Compile the files:

javac *.java


Run the program:

java Main

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/5c3cb554-02d2-4418-9538-2b1f11c58842" />

Reflections

Inheritance helped simplify the structuring of code, as it allowed all vehicles to use the common properties and methods of the Vehicle class. This reduced code duplication and made the program more understandable.

Method overriding allowed each vehicle to have its own behavior when starting and stopping the engine. A small challenge was understanding how the protected and default access modifiers work and when they should be applied.
