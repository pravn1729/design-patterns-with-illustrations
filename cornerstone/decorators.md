# Decorators

## Background
I am learning about Angular2 recently. There is concept called decorators that is borrowed from Python. So I want to figure it out first before moving on.


![Gun](http://qxf2.com/blog/wp-content/uploads/2014/09/qxf2-gun-decorator1.jpg)
-- [Understanding Python decorators](https://qxf2.com/blog/python-decorators/)

## What?

> 每个人都有的内裤主要功能是用来遮羞，但是到了冬天它没法为我们防风御寒，咋办？我们想到的一个办法就是把内裤改造一下，让它变得更厚更长，这样一来，它不仅有遮羞功能，还能提供保暖，不过有个问题，这个内裤被我们改造成了长裤后，虽然还有遮羞功能，但本质上它不再是一条真正的内裤了。于是聪明的人们发明长裤，在不影响内裤的前提下，直接把长裤套在了内裤外面，这样内裤还是内裤，有了长裤后宝宝再也不冷了。**装饰器就像我们这里说的长裤**，在不影响内裤作用的前提下，给我们的身子提供了保暖的功效。


> **装饰器本质上是一个Python函数，它可以让其他函数在不需要做任何代码变动的前提下增加额外功能，装饰器的返回值也是一个函数对象。**它经常用于有切面需求的场景，比如：*插入日志、性能测试、事务处理、缓存、权限校验*等场景。装饰器是解决这类问题的绝佳设计，有了装饰器，我们就可以**抽离出大量与函数功能本身无关的雷同代码并继续重用**。概括的讲，**装饰器的作用就是为已经存在的对象添加额外的功能。**

-- [理解 Python 装饰器看这一篇就够了](https://foofish.net/python-decorator.html)


## Why?

![装饰模式](https://design-patterns.readthedocs.io/zh_CN/latest/_images/Decorator.jpg)

1. Analytics, logging, and instrumentation
2. Validation and runtime checks
3. Creating frameworks
4. Reusing impossible-to-reuse code
5. Boosting your career

> -- [5 reasons you need to learn to write Python decorators](https://www.oreilly.com/ideas/5-reasons-you-need-to-learn-to-write-python-decorators)


## How?
- [Logging actions with Python decorators Part I: Decorating logged functions](https://www.freshbooks.com/assets/blog-uploads/img/DecoratorsVisuallyExplained.png)
- [How do they work](https://image.slidesharecdn.com/decorators-2-140907225936-phpapp02/95/decorators-explained-a-powerful-tool-that-should-be-in-your-python-toolbelt-15-638.jpg?cb=1410252461)
- [Python Decorators](https://www.programiz.com/python-programming/decorator)

### Real stories

- [Code. Changing it without breaking it, using a Decorator.](https://dev.to/kchawla_pi/using-a-decorators-to-solve-my-task-the-thinking--the-process-49f0)


## Reference

1. [The Basics of Python Decorators](https://www.youtube.com/watch?v=mZ5IwFfqvz8)
2. [理解 Python 装饰器看这一篇就够了](https://foofish.net/python-decorator.html)
3. [Python Decorators](https://www.programiz.com/python-programming/decorator)
4. [5 reasons you need to learn to write Python decorators](https://www.oreilly.com/ideas/5-reasons-you-need-to-learn-to-write-python-decorators)
5. [Using Python decorators to be a lazy programmer: a case study](http://www.onthelambda.com/2016/07/08/using-python-decorators-to-be-a-lazy-programmer-a-case-study/)
6. [如何理解Python装饰器？](https://www.zhihu.com/question/26930016)
7. [图解设计模式：3. 装饰模式](https://design-patterns.readthedocs.io/zh_CN/latest/structural_patterns/decorator.html#id7)
8. [Understanding Python decorators](https://qxf2.com/blog/python-decorators/)