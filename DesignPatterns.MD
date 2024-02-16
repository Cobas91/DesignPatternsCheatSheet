# Design patterns
## Design Pattern Categories

- Creational Patterns
  - Chain of Responsibility
  - Command
  - Interpreter
  - Iterator
  - Mediator
  - Memento
  - Observer
  - State
  - Strategy
  - Template Method
  - Visitor
- Structural Patterns
  - Adapter
  - Bridge
  - Composite
  - Decorator
  - Facade
  - Flyweight
  - Proxy
- Behavioural Patterns
  - Abstract
  - Builder
  - Factory
  - Prototype
  - Singelton

![img.png](images/overview.png)

## Singelton

### Usage: 

Use when a single instance of a class is needed. Some examples are logging and database connections.

![img.png](images/singelton.png)


## Factory

### Usage:

Decouple object creation from usage. For example, you create different types of database connections based on configuration.

![img.png](images/factory.png)

## Builder

### Usage:

Constructing complex objects step by step. For example, if you need to create a complex domain object.

![img.png](images/builder.png)

## Adapter

### Usage:

Make incompatible interfaces compatible. For example, it integrates a new logging library into an existing system that expects a different interface.

![img.png](images/adapter.png)

## Composite

### Usage:

Represent part-whole hierarchies. For example, graphic objects in a drawing application can be grouped and treated uniformly.

![img.png](images/composite.png)

## Proxy

### Usage:

Control access to objects. For example, lazy loading of a high-resolution image in a web application.

![img.png](images/proxy.png)

## Decorator

### Usage:

Dynamically add/remove behavior. For example, we are implementing compression or encryption on top of file streams.

![img.png](images/decorator.png)

## Strategy

### Usage:

Define a family of algorithms. For example, they allow users to choose different sorting or compression algorithms.

![img.png](images/strategy.png)

## Observer

### Usage:

Maintain a consistent state by being notified of changes and, for example, notifying subscribers of events in a messaging system.

![img.png](images/observer.png)

## Command

### Usage:

Encapsulate a request as an object. For example, I implement undo/redo functionality in text or image editor.

![img.png](images/command.png)

## State

### Usage:

Encapsulate state-specific behavior. For example, we are handling different states of a user interface element (e.g., enabled, disabled, selected).

![img.png](images/state.png)

## Template Method

## Usage:

Define the skeleton of an algorithm in operation, deferring some steps to subclasses and implementing a base class for unit testing with customizable setup and teardown steps.

![img.png](images/template_method.png)



![img.png](images/how_to_select.png)



# Resources

- https://newsletter.techworld-with-milan.com/p/how-to-select-a-design-pattern?ref=dailydev
