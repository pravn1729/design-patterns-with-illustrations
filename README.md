# Design patterns with illustrations

## Features

- before and after 
- get the intuition by pictures

## Design pattern

### Creational 
Creational design patterns are concerned with **how objects are created.** Normally we create objects by calling their constructor (i.e., **calling their class object with arguments**), but sometimes we need more **flexibility** in how objects are created — which is why the creational design patterns are useful.

For Python programmers, some of these patterns are fairly similar to each other — and some of them, as we will note, aren’t really needed at all. This is because the original design patterns were primarily created for the **C++ language** and needed to work around some of that language’s limitations. **Python doesn’t have those limitations.**

| key 🔑 | why | what  | how  | when | 
| :-------- | :---------: | :----------: | :---------: |  :---------: |
|**Simple Factory🏠**| create without the mess | class | `new`| |
|**Factory Method🏭**| generic & sub-class | subclass| `extends`| |
|**Abstract Factory🔨**| stuff & steps | interface? |`implements`| dependencies |
|**Builder👷**| to avoid the constructor telescoping | multi steps|`new`&   `function`  | |
|**Prototype🐑**| similar & save | copy | `clone` |  |
|**Singleton💍**|  unique| president of a country| `getInstance()` | ⚠️|



- [x] **Simple Factory🏠**: Simple factory simply **generates an instance for client without exposing any instantiation logic** to the client e.g. door 
- [ ] Factory Method🏭: It provides a way to **delegate** the instantiation logic to child classes. e.g. take interview
- [ ] Abstract Factory🔨: A factory of factories e.g. door & experts
- [ ] Builder👷: Separates object **construction** from its **representation** e.g. Subway 
- [ ] Prototype🐑 
- [ ] Singleton💍

### Structural 
The primary concern of structural design patterns is **how objects are composed together to form new, larger objects.**

Three themes stand out in structural design patterns: adapting interfaces, adding functionality, and handling collections of objects.


| key 🔑 | why | what  | how  | when | 
| :-------- | :---------: | :----------: | :---------: |  :---------: |
|**Adapter🔌**| | **incompatible** -> **compatible**  <br>e.g. card reader, power adapter.| `WildDogAdapter`||
|Bridge🚡|composition over inheritance| decouple & independently||
|Composite🌿| uniform |group → same single |
|Decorator☕|dynamically change|<img src="http://qxf2.com/blog/wp-content/uploads/2014/09/qxf2-gun-decorator1.jpg" alt="Decorator" width="200"/>|[python](https://repl.it/@WillWang42/decorator)| **切面需求**<br>e.g.<br>插入日志<br>性能测试<br>事务处理<br>缓存<br>权限校验|
|Facade📦|simplified interface → complex subsystem |<img src="https://i.imgur.com/bYMfJAx.jpg" alt="Facade" width="200"/> <br>e.g. hit the button ||
|Flyweight🍃|sharing & frugality|<img src="https://i.imgur.com/o3ClHZv.jpg" alt="Flyweight" width="200"/>||
|Proxy🎱|extra functionality|<img src="https://i.imgur.com/tHIXbE8.png" alt="Proxy" width="200"/> <br>|`function`+||

- Adapter
- Bridge
- Composite
- Decorator
- Facade
- Flyweight
- Proxy

### Behavioral                 
The behavioral patterns are concerned with **how things get done**; that is, with algorithms and object interactions. They provide powerful ways of thinking about and organizing computations, and like a few of the patterns seen in the previous two chapters, some of them are supported directly by built-in Python syntax.

The Perl programming language’s well-known motto is, “there’s more than one way to do it”; whereas in Tim Peters’ Zen of Python, “there should be one—and preferably only one—obvious way to do it”. Yet, like any programming language, there are sometimes two or more ways to do things in Python, especially since the introduction of comprehensions (use a comprehension or a for loop) and generators (use a generator expression or a function with a yield statement). And as we will see in this chapter, Python’s support for coroutines adds a new way to do certain things.



| key 🔑 | why | what  | how  | when | 
| :-------- | :---------: | :----------: | :---------: |  :---------: |
|Chain of Responsibility🔗|request with multi handle|<img src="https://i.imgur.com/EyoYZbI.png" alt="Chain of Respnsibility" width="200"/> <br>|`setNext`| |
|Comand|encapsulate actions in objects|<img src="https://i.imgur.com/Z2jMgb2.png" alt="Command" width="200"/> <br>|`Client` & `Invoker` & `Command` & `Receiver` ||
|Iterator➿|what's next|<img src="https://i.imgur.com/IlKj1J3.jpg" alt="Iterator" width="200"/> <br>|`next`|
| Mediator👽|encapsulate interact|<img src="https://i.imgur.com/JuoIurx.jpg" alt="Mediator" width="200"/> <br>|meidator & user|
| Memento|redo|<img src="https://i.imgur.com/dGzcnqh.png" alt="Memento" width="200"/> <br>|`save`|
| Observer | subscribe & notice |<img src="https://i.imgur.com/iIpUCr3.png" alt="Observer" width="200"/> <br>|`attach`|
|[Visitor](https://www.wikiwand.com/en/Visitor_pattern)🚕|add more without modify|<img src="https://i.imgur.com/8RWeDoc.png" alt="Visitor" width="200"/> <br> | `interface`| |
|Strategy|choose x suitable|<img src="https://i.imgur.com/wX1y2jT.png" alt="Strategy" width="200"/> <br>|`if`||
|State|state → class|<img src="https://i.imgur.com/zh3pkxI.jpg" alt="state" width="200"/> <br>|`interface` & `class` & `function`||
|Template| skeleton → children classes|




- [ ] Chain of Responsibility🔗
- [ ] Command👮
- [ ] Iterator➿: An iterator returns items from a collection one at a time until it has returned all items from the collection.
- [ ] Mediator👽: In software engineering, the mediator pattern defines an object that **encapsulates** how a set of objects interact. This pattern is considered to be a behavioral pattern due to the way it can alter the program's running behavior.
- [ ] Memento💾: The memento pattern is a software design pattern that provides the ability to restore an object to its previous state (undo via rollback).
- [ ] Observer😎: Defines a dependency between objects so that whenever an object changes its state, all its dependents are notified.
- [ ] Visitor🏃: Visitor pattern lets you add further operations to objects without having to modify them.
- [ ] Strategy💡: Strategy pattern allows you to switch the algorithm or strategy based upon the situation.
- [ ] State💢: It lets you change the behavior of a class when the state changes.
- [ ] Template Method📒：Template method defines the **skeleton** of how a certain algorithm could be performed, but defers the implementation of those steps to the children classes.



## Reference

- [python in practice](https://github.com/lovexiaov/python-in-practice)
- [design patterns for humans](https://github.com/kamranahmedse/design-patterns-for-humans)
- [Design Patterns Game](http://designpatternsgame.com/)
- [dive into design patterns](https://sourcemaking.com/design_patterns)
- [Design Patterns Illustrated](https://www.slideshare.net/HermanPeeren/design-patterns-illustrated/37-Iterator_Enable_sequential_access_to)
- [Object-Oriented Design Patterns in Life](https://www.sihui.io/design-patterns/)
- [Refactoring](https://refactoring.guru/design-patterns/catalog)


## More 

- [Understanding The Visitor Design Pattern](https://www.youtube.com/watch?v=TeZqKnC2gvA)
