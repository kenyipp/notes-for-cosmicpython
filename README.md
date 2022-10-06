# Cosmic Python
It is the study note of mine for the book [Cosmic Python](https://www.cosmicpython.com). I create this note for revision and preparation for the next job interview. I am not a python developer but still learn a lot from this book.

### Encapsulation and Abstractions
Help us by hiding details and protecting the consistency of our data.

 - **Encapsulation** - Simplifying behavior and hiding data
 - **Abstraction** - The public interface / API of the thing you are using

### Layering
Divide our code into discrete categories or roles, and we introduce rules about which categories of code can call each other.

The most common example is the three-layered architecture
Presentation Layer -> Business Logic -> Database Layer

### SOLID Principle
[![Solid Principle](https://miro.medium.com/max/1400/1*jNx5bZR301i1gb4Dq_qzMQ.png)](https://medium.com/bgl-tech/what-are-the-solid-design-principles-c61feff33685)

### The Dependency Inversion Principle

1. High-level modules should not depend on low-level modules. Both should depend on abstractions.
2. Abstractions should not depend on details. Instead, details should depend on abstractions.

Our business codes should not depend on the technical details. Instead, both should use abstractions. 

### Behavior should come first and drive our storage requirements
To implement that practice, there are four key design patterns:
 - **Repository Pattern** - an abstraction over the idea of persistent storage
 - **Server Layer** - clearly define where our use cases begin and end
 - **Unit of Work pattern** - provide atomic operations
 - **Aggregate pattern** - enforce the integrity of our data
