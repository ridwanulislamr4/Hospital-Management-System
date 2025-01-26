# Hospital-Management-System
The provided Java code implements a simple Hospital Management System using the principles of Object-Oriented Programming (OOP), specifically focusing on Inheritance, Polymorphism, Encapsulation, and Abstraction.

1. **Abstraction**: The `Person` class is an abstract class that defines common properties and methods for all persons in the system. It includes private fields for `name`, `age`, and `gender`, and abstract method `displayInfo()` which must be implemented by subclasses.

2. **Encapsulation**: The fields in the `Person` class are private and accessed via public getter and setter methods. This ensures that the internal state of an object is protected from unauthorized access and modification.

3. **Inheritance**: The `Doctor` and `Patient` classes inherit from the `Person` class. They extend the functionality of the `Person` class by adding specific attributes (`specialty` for `Doctor` and `ailment` for `Patient`) and providing their own implementation of the `displayInfo()` method.

4. **Polymorphism**: The `displayInfo()` method is overridden in both `Doctor` and `Patient` classes. This allows the same method to behave differently based on the object that invokes it.
