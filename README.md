# Design patterns with illustrations

## Features

- before and after 
- get the intuition by pictures

## Design pattern

### Creational 
Creational design patterns are concerned with **how objects are created.** Normally we create objects by calling their constructor (i.e., **calling their class object with arguments**), but sometimes we need more **flexibility** in how objects are created — which is why the creational design patterns are useful.

For Python programmers, some of these patterns are fairly similar to each other — and some of them, as we will note, aren’t really needed at all. This is because the original design patterns were primarily created for the **C++ language** and needed to work around some of that language’s limitations. **Python doesn’t have those limitations.**

- [ ] **Simple Factory🏠**: Simple factory simply **generates an instance for client without exposing any instantiation logic** to the client e.g. 
- [ ] Factory Method🏭: It provides a way to **delegate** the instantiation logic to child classes. e.g. take interview
- [ ] Abstract Factory🔨: A factory of factories
- [ ] Builder👷: Separates object **construction** from its **representation** e.g. Subway 
- [ ] Prototype🐑 
- [ ] Singleton💍

### Structural 
The primary concern of structural design patterns is **how objects are composed together to form new, larger objects.**

Three themes stand out in structural design patterns: adapting interfaces, adding functionality, and handling collections of objects.


| key 🔑 | why | what  | how  | when | 
| :-------- | :---------: | :----------: | :---------: |  :---------: |
|**Adapter🔌**| | **incompatible** -> **compatible**  <br>e.g. card reader, power adapter.| ||
|Bridge🚡||||
|Composite🌿|
|Decorator☕||<img src="http://qxf2.com/blog/wp-content/uploads/2014/09/qxf2-gun-decorator1.jpg" alt="Decorator" width="200"/>|[python](https://repl.it/@WillWang42/decorator)| **切面需求**<br>e.g.<br>插入日志<br>性能测试<br>事务处理<br>缓存<br>权限校验|
|Facade📦|
|Flyweight🍃|
|Proxy🎱|


### Behavioral                 
The behavioral patterns are concerned with **how things get done**; that is, with algorithms and object interactions. They provide powerful ways of thinking about and organizing computations, and like a few of the patterns seen in the previous two chapters, some of them are supported directly by built-in Python syntax.

The Perl programming language’s well-known motto is, “there’s more than one way to do it”; whereas in Tim Peters’ Zen of Python, “there should be one—and preferably only one—obvious way to do it”. Yet, like any programming language, there are sometimes two or more ways to do things in Python, especially since the introduction of comprehensions (use a comprehension or a for loop) and generators (use a generator expression or a function with a yield statement). And as we will see in this chapter, Python’s support for coroutines adds a new way to do certain things.



| key 🔑 | why | what  | how  | when | 
| :-------- | :---------: | :----------: | :---------: |  :---------: |
|[Visitor](https://www.wikiwand.com/en/Visitor_pattern)🚕|add more without modify| | | |


- [ ] Chain of Responsibility🔗
- [ ] Command👮
- [ ] Iterator➿
- [ ] Mediator👽
- [ ] Memento💾 
- [ ] Observer😎 
- [ ] Visitor🏃
- [ ] Strategy💡
- [ ] State💢
- [ ] Template Method📒 


## Reference

- [python in practice](https://github.com/lovexiaov/python-in-practice)
- [design patterns for humans](https://github.com/kamranahmedse/design-patterns-for-humans)
- [Design Patterns Game](http://designpatternsgame.com/)
- [dive into design patterns](https://sourcemaking.com/design_patterns)


## More 

- [Understanding The Visitor Design Pattern](https://www.youtube.com/watch?v=TeZqKnC2gvA)
