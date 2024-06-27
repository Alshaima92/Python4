
Methods of the Class and Static Methods:
========================================

- The class attributes are common to all instances in a class.
  
- Class methods work on the class itself, which takes cls as an argument. They can be used to change the state of a class.(Use @classmethod decorator).
  
- Static methods are not associated with any object or instance variables and do not modify anything about the class (may use @staticmethod decorator).
  
Encapsulation:
--------------

- Preventing access to certain parts of an object with private (__) or protected (_) attributes/methods.
  
- Properties make it possible to control attribute access and modification.
  
Abstract Classes and Methods:
------------------------------

- A blueprint for subclasses is provided by abstract classes but they themselves cannot be instantiated.
  
- In an abstract class, there are abstract methods which are not implemented. Subclasses must provide concrete implementations. (Use ABC and abstractmethod from abc module).
  
Multiple Inheritance:
---------------------
- A child class inherits from more than one parent class, which means that it has access to their attributes and methods.
  
- Method Resolution Order (MRO) resolves conflicts during multiple inheritance situations.
  
Method Chaining:
----------------
- Dot notation lets methods return self thereby allowing you to chain them together in one line.

Notes:
-------
- Private attributes and methods in Python are not private since they can be accessed using name-mangling techniques.
  
- Abstraction is aimed at concealing implementation details and making functionality available to users.

