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


![Hierarchy of the collection framework](https://github.com/vishwadhwaj/vishwadhwaj-kumar/blob/master/Java-Collections-Framework-Hierarchy.png)


All the required classes and interfaces by the collection framework is present in utility package(java.util).The collection interface framework has an iterable interface which provides the iterator to iterate through the collection.This interface is extended by the collection interface.Collection interface is the root interface of the collection framework.It is extended by all the collections and thus also implements the iterable interface and thereby have access to the methods of iterable interface.For knowing the methods of the collection interface refer to [this](https://www.geeksforgeeks.org/collections-in-java-2/).


### Interfaces in the collection framework


Collection framework has multiple interfaces where every interface is used to store specific type of data.Few are the interfaces in the collection framework.


1. **Iterable Interface** - It is extended by all the interfaces and the collection classes in the collection framework.Collection interface implements this interface thereby inhereting all the properties of iterator in it.It essentially provides the iterator for the collections and hence it has only one abstract method which is iterator.

> Iterator iterator();


2. **Collection Interface** - It extends the iterable interface and it is implemented by all the collections in collection framework.It has all the methods for performing the operations that is performed on every collection.We can add the data,remove the data,get the data,clear the data etc..All the methods for all such operations are present in this interface and is implemented by all the collections that extended these methods.These implementations are based on the design of the collections and these methods are implemented irrespective of the style of implementations of all the collections.It provides the base for building all the collections classes.


**Following are the interfaces which implements Collection interface**

* **List Interface** - This is child of the Collection Interface.It provides the methods which are implemented by the list type of data in which ordered collection of object is stored.The classes which implements this interface can be known from [here](https://www.geeksforgeeks.org/collections-in-java-2/).Since all the subclasses implement this interface we can instantiate object of any class using this interface. 


* **Queue Interface** - It maintains the FIFO(First In First Out) order.It means that the element that is added first in the Collection will be removed first.It is used by those data in which order of elements matter.All the classes listed [here](https://www.geeksforgeeks.org/collections-in-java-2/) are those which implements the queue interface.Since all these are subclasses we can instantiate the objects of these classes using this interface. 

* **Set Interface** - It is an unordered collection of objects in which no duplicate elements can be stored.It is when we wnat to store only unique objects in the collection and avoid duplicacy.All the classes mentioned [here](https://www.geeksforgeeks.org/collections-in-java-2/) are the classes which implements the set interface. 

* **Map Interface** - It supports key value pair mapping of the data.It does not contain duplicate keys as one key cannot have multiple mapping.This data structure provides fast seraching of data and searches the data based on the key.It also performs other operations using the key.All the sub classes that implements this interface are mentioned [here](https://www.geeksforgeeks.org/collections-in-java-2/)


## Reference

[Java Collections](https://www.geeksforgeeks.org/collections-in-java-2/) 
