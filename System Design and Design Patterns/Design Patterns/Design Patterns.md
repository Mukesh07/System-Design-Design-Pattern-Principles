#Creational desgin patterns
- Factory method: Provides interface for creating objects in a superclass, but allows    subclasses to alter the type of objects that will be created.
- Abstract factory method: Produces families of related objects without specifying their concrete classes.
- Builder: Construct complex objects step by step. The pattern allows to produce different types and representations of an object using the same construction code.
- Prototype: Copy existing objects without making your code dependent on their classes.
- Singleton: Ensures that a class has only one instance, while providing a global access point to this instance.

#Structural design patterns
- Adapter: Allows objects with incompatible interfaces to collaborate.
- Bridge: Split a large class or a set of closely related classes into two separate hierarchies—abstraction and implementation—which can be developed independently of each other.
- Composite: Compose objects into tree structures and then work with these structures as if they were individual objects.
- Decorator: Attach new behaviors to objects by placing these objects inside special wrapper objects that contain the behaviors.
- Facade: Provides a simplified interface to a library, a framework, or any other complex set of classes.
- Flyweight: Fit more objects into the available amount of RAM by sharing common parts of state between multiple objects instead of keeping all of the data in each object.
- Proxy: Provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.

#Behavioural design patterns
- Chain of responsibility: Pass requests along a chain of handlers. Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain.
- Command: Turns a request into a stand-alone object that contains all information about the request. This transformation lets you pass requests as a method arguments, delay or queue a request’s execution, and support undoable operations.
- Iterator: Traverse elements of a collection without exposing its underlying representation (list, stack, tree, etc.).
- Mediator: reduce chaotic dependencies between objects. The pattern restricts direct communications between the objects and forces them to collaborate only via a mediator object.
- Memento: Save and restore the previous state of an object without revealing the details of its implementation.
- Observer: Define a subscription mechanism to notify multiple objects about any events that happen to the object they’re observing.
- State
- Strategy
- Template method
- Visitor