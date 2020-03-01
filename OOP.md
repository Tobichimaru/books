# Object-oriented programming

**Object-oriented programming** is the successor of procedural (structural) programming. 
Procedural programming describes programs as groups of reusable code units (procedures) 
which define input and output parameters. Procedural programs consist of procedures, which invoke each other.

The problem with procedural programming is that code reusability is hard and limited –
only procedures can be reused and it is hard to make them generic and flexible. 
There is no easy way to work with abstract data structures with different implementations.

The object-oriented approach relies on the paradigm that each and every program works with data that describes 
entities(objects or events) from real life. For example: accounting software systems work with invoices, items,
warehouses, availabilities, sale orders, etc.

The main advantages and goals of OOP are to make complex software faster to develop and easier to maintain. 
OOP enables the easy reuse of code by applying simple and widely accepted rules (principles). Let’s check them out.

In order for a programming language to be object-oriented, it has to enable working with classes and objects 
as well as the implementation and use of the fundamental object-oriented principles and concepts: 
**inheritance, abstraction, encapsulation and polymorphism**. 

Let’s summarize each of these fundamental principles of OOP:
### Encapsulation
hide unnecessary details in classes and provide a clear and simple interface for working with them. It is also called "information hiding". An object has to provide its users only with the essential information for manipulation, without the internal details.
### Inheritance
Inheritance is a fundamental principle of object-oriented programming. It allows a class to "inherit" (behavior or characteristics) of another, more general class.
### Abstraction
Abstraction means working with something we know how to use without knowing how it works internally. We can work with an abstract data type by using its interface without concerning ourselves with its implementation. For instance, we can save to a file all elements from a list without bothering if it is implemented with an array, a linked list, etc. 
Abstraction allows us to do something very important – define an interface for our applications, i.e. to define all tasks the program is capable to execute and their respective input and output data. 
### Polymorphism
Polymorphism allows treating objects of a derived class as objects of its base class. Polymorphism can bear strong resemblance to abstraction, but it is mostly related to overriding methods in derived classes, in order to change their original behavior inherited from the base class

### Cohesion and Coupling (связанность и связность)
**Cohesion** refers to what the class (or module) can do. Low cohesion would mean that the class does a great variety of actions - it is broad, unfocused on what it should do. High cohesion means that the class is focused on what it should be doing, i.e. only methods relating to the intention of the class.

As for **coupling**, it refers to how related or dependent two classes/modules are toward each other. For low coupled classes, changing something major in one class should not affect the other. High coupling would make it difficult to change and maintain your code; since classes are closely knit together, making a change could require an entire system revamp.
Good software design has **high cohesion and low coupling**.

### Object-oriented modeling (OOM)

Object-oriented modeling (OOM) is a process associated with OOP where all objects related to the problem we are solving are brought out (a model is created)
Object-oriented modeling is usually performed in these steps:
* Identification of classes.
* Identification of class attributes.
* Identification of operations on classes.
* Identification of relations between classes.



