# Design Patterns in Programming

This repository contains a list of common design patterns in programming, categorized into three main groups: creational, structural, and behavioral patterns. These patterns are foundational concepts that help make code more flexible, reusable, and maintainable.

## Table of Contents

### 1. Creational Patterns

Creational patterns focus on object creation mechanisms, trying to create objects in a manner suitable to the situation. These patterns help control object creation and ensure that the objects are created in a way that suits the needs of the application, promoting code reusability and scalability.

- **Singleton**: Ensures a class has only one instance and provides a global point of access. This pattern is useful when exactly one object is needed to coordinate actions across a system. [Example](https://github.com/MansourJouya/DesignPattern-Singleton)
- **Factory**: This repository showcases implementations of the Factory design pattern in various programming languages, including C#, C++, Python, JavaScript, Visual Basic, and F#. Each example demonstrates how to create objects without specifying the exact class of the object that will be created. [Example](https://github.com/MansourJouya/DesignPattern-Factory)
- **Abstract Factory**: Provides an interface for creating families of related or dependent objects without specifying their concrete classes. This pattern helps create related objects that belong to a family without the client needing to know the specific classes. [Example](https://github.com/MansourJouya/DesignPattern-AbstractFactory)
- **Builder**: Separates the construction of a complex object from its representation so that the same construction process can create different representations. This pattern is ideal for creating complex objects step by step and allows for flexible object creation. [Example](https://github.com/MansourJouya/DesignPattern-Builder)
- **Prototype**: Creates new objects by copying an existing object, known as a prototype. This pattern is useful when the cost of creating a new object is higher than copying an existing one, and it helps maintain object consistency. [Example](https://github.com/MansourJouya/DesignPattern-Prototype)

### 2. Structural Patterns

Structural patterns deal with the composition of classes or objects and help ensure that they are composed in a way that is efficient and flexible. These patterns help simplify complex structures by organizing classes and objects into more manageable and modular forms.

- **Adapter (or Wrapper)**: Allows incompatible interfaces to work together by converting one interface into another. This pattern is useful for making existing classes compatible with new systems without modifying their code. [Example](https://github.com/MansourJouya/DesignPattern-Adapter)
- **Decorator**: Adds new functionality to an object dynamically at runtime. This pattern is often used to extend the behavior of an object without altering its structure. [Example](https://github.com/MansourJouya/DesignPattern-Decorator)
- **Facade**: Provides a simplified interface to a larger body of code, such as a complex subsystem. This pattern hides the complexities of the subsystem and provides a unified interface to the client. [Example](https://github.com/MansourJouya/DesignPattern-Facade)
- **Proxy**: Provides a surrogate or placeholder for another object to control access to it. This pattern can be used to add functionality like caching, lazy initialization, or access control. [Example](https://github.com/MansourJouya/DesignPattern-Proxy)
- **Bridge**: Decouples an abstraction from its implementation so that the two can vary independently. This pattern helps in building scalable and maintainable code by separating the abstraction and its implementation. [Example](https://github.com/MansourJouya/DesignPattern-Bridge)
- **Composite**: Composes objects into tree-like structures to represent part-whole hierarchies. This pattern helps treat individual objects and composites uniformly, which is useful for implementing complex tree structures. [Example](https://github.com/MansourJouya/DesignPattern-Composite)

### 3. Behavioral Patterns

Behavioral patterns are concerned with algorithms and the assignment of responsibilities between objects. These patterns focus on how objects communicate and collaborate, facilitating complex workflows and interactions between objects.

- **Observer**: Allows an object (subject) to maintain a list of its dependents (observers) and notify them of state changes. This pattern is ideal for implementing distributed event-handling systems. [Example](https://github.com/MansourJouya/DesignPattern-Observer)
- **Strategy**: Defines a family of algorithms, encapsulates each one, and makes them interchangeable. This pattern enables selecting an algorithm's behavior at runtime and provides a clean way to implement polymorphism. [Example](https://github.com/MansourJouya/DesignPattern-Strategy)
- **Command**: Encapsulates a request as an object, allowing users to parameterize clients with queues, requests, and operations. This pattern is helpful for implementing undo/redo functionality and transactional behavior. [Example](https://github.com/MansourJouya/DesignPattern-Command)
- **State**: Allows an object to change its behavior when its internal state changes. This pattern is useful for implementing state-dependent behavior and avoiding complex conditional statements. [Example](https://github.com/MansourJouya/DesignPattern-State)
- **Mediator**: Defines an object that encapsulates how a set of objects interact, promoting loose coupling. This pattern is useful for managing communication between objects without them needing to reference each other directly. [Example](https://github.com/MansourJouya/DesignPattern-Mediator)
- **Memento**: Captures and restores an object's state without exposing its details. This pattern is useful for implementing undo/redo functionality in applications. [Example](https://github.com/MansourJouya/DesignPattern-Memento)
- **Iterator**: Provides a way to access the elements of a collection sequentially without exposing its underlying representation. This pattern helps provide a consistent way to traverse elements in different data structures. [Example](https://github.com/MansourJouya/DesignPattern-Iterator)
- **Template Method**: Defines the skeleton of an algorithm in an operation, deferring some steps to subclasses. This pattern helps avoid code duplication and promotes code reusability. [Example](https://github.com/MansourJouya/DesignPattern-TemplateMethod)
- **Visitor**: Allows you to define a new operation without changing the classes of the elements on which it operates. This pattern is useful for adding further operations to existing object structures. [Example](https://github.com/MansourJouya/DesignPattern-Visitor)
- **Chain of Responsibility**: Passes a request along a chain of handlers until one handles it. This pattern is useful for decoupling sender and receiver objects and enabling multiple objects to process a request. [Example](https://github.com/MansourJouya/DesignPattern-ChainOfResponsibility)

