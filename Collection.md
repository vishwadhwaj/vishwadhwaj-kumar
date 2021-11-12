# JAVA COLLECTIONS



Group of individual objects which are considered as single unit is called as collections.Java collections is essentially a framework that contains all the collection classes and the interface implemented by them.


### What is a framework?


A framework is an architecture which provide sets of classes and interfaces to develop new feature or classes by using them.The frameworks in object oriented design includes classes such that all the classes perform same kind of task.


### Situation before Collection framework


Before collection framework all the collections like array,Vectors,Hashtable,Linkedlist etc. had different implementations for performing same kind of tasks.All these implementations do not have correlation between them as they do not have common interface for performing same kind of tasks.That's why users have difficulty remembering the syntax and methods and constructors in all the collection classes.So it was very difficult to write algorithms that work for all the collections.Also in some collections the method are final so users cannot extend them to create their own implementation for all these methods.


### After Collection Framework


1. **Consistent API** - The Api has interfaces like *Collection*,*set*,*list* and *map* which are inplemented by collections like arraylist,vectors,linkedlist etc.All these collections that implement these interfaces have common set of methods.

2. **Less Programming effort** - The programmer does not have to know about the design of collections or the implementation of the collections,he can just use the methods which are common for performing same kind of task in all the collections.By this way abstraction principle of object oriented design is also implemented.  

3. **Provides efficient implementation** - Optimised implementation of data structures and algorithms gives programmer lead to do their necessary tasks without caring about the optimum implementation of certain algorithms or data structures.for example sorting is implemented using quick sort,So it is the optimised implementation.That's why when programmers want to have optimised time complexity they can just use it without caring about the implementations.


### Hierarchy of the collection framework



