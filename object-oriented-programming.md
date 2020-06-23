**Literature**

- [ ] [Fundamentals of Object Oriented Programming](https://en.wikipedia.org/wiki/Object-Oriented_Software_Construction)
- [ ] [Domain-Driven-Design](https://en.wikipedia.org/wiki/Domain-driven_design)

**OOP checklist**

- [ ] What is OOP?
- [ ] What is a class?
- [ ] What is an object?
- [ ] What is a class hierarchy?
- [ ] What is an abstract class and abstract method?
- [ ] What is a static method? Is a class from static methods only an OOP class?
- [ ] What are the features of each of the main types of relations between classes: composition, aggregation, inheritance, association?
- [ ] How is composition different from inheritance?
- [ ] What is polymorphism? What is it used for?
- [ ] What is encapsulation? What problems are solved with its help?
- [ ] What is the state of the program? How does it affect the program?
- [ ] What are side effects?
    - Do I have to deal with side effects when designing in the OOP paradigm?
    - Are mutations a side effect?
- [ ] What are the principles of SOLID? What does each letter of the acronym mean?
- [ ] What is identity? What is the difference from an instance?
- [ ] How are identity implemented through references to values ​​in memory?
- [ ] What are dynamic and static polymorphisms in the context of OOP?
- [ ] How do polymorphism and interfaces allow dependency inversion to be implemented?
- [ ] What are some ways to extend the functionality of a class?
- [ ] What are the challenges of using inheritance?
- [ ] What is delegation?
- [ ] Why does a class define a behavior, not a property? And what about encapsulation?
- [ ] Why is the use of plain old javascript objects not complying with the principle "everything is an object"?

**OOD checklist**

- [ ] What is abstraction? What are the differences between abstraction, encapsulation, and information hiding?
- [ ] What is Coupling? How does abstraction affect coupling?
- [ ] What is Cohesion? Is this value the reciprocal of Coupling?
- [ ] Separation of concerns
    - What it is?
    - What are the benefits of following this principle?
    - What do horizontal and vertical separation of concerns mean?
    - Is vertical separation possible without horizontal and vice versa?
    - How is it associated with the Single Responsibility Principle and with cohesion?
- [ ] Simplicity
    - How does Rich Hickey in his report "Simple Made Easy" describe the difference between Simple and Easy? Why in the first place is it striving for simplicity, and not for ease?
    - What is the KISS principle?
    - How does KISS help in building mental models? What is the value of these models?
    - How can participating in the development of business requirements help follow KISS?
    - When is abstraction contrary to KISS?
    - Why inheritance can lead to violation of KISS?
    - What is the principle of YAGNI? How does it compare with the KISS principle?
- [ ] DRY
    - What is the main idea of ​​the DRY principle?
    - How is the principle related to Cohesion?
    - How is the principle related to the principle of SRP?
    - Why is this principle inextricably linked with SPOT (Single point of truth)?
    - What are some examples of code duplication that do not violate DRY?
    - What are some examples of copying business logic code that also do not violate DRY?
    - How can following the DRY principle lead to a violation of KISS?
    - How can following the DRY principle lead to Premature Generalization?
    - Why, when trying to remove duplication, when there are still few repetitions of this code (up to 4-5), we can easily make a mistake and choose the wrong refactoring method? What is the analogy with statistics?
    - How do you explain the phrase "Duplication is far cheaper than the wrong abstraction."?
- [ ] What are Cross-cutting concerns? What does coarse-grained and fine-grained responsibility mean?

**OOP Resources**

1. [Сайд эффекты](http://blog.csssr.ru/2017/10/07/side-effects)
2. [Composition vs inheritance](https://javarevisited.blogspot.com/2013/06/why-favor-composition-over-inheritance-java-oops-design.html)
3. [Наследование vs Композиция vs Агрегация](http://sergeyteplyakov.blogspot.com/2012/12/vs-vs.html)
4. [Uses and Abuses of Inheritance, Part 1](http://www.gotw.ca/publications/mill06.htm)
5. [Uses and Abuses of Inheritance, Part 2](http://www.gotw.ca/publications/mill07.htm)
6. [Принципы проектирования классов (S.O.L.I.D.)](https://blog.byndyu.ru/2009/10/solid.html)
7. [OTA SOLID (интерактивный ресурс)](https://ota-solid.now.sh/)
8. [SOLID Principles with Uncle Bob - Robert C. Martin](https://www.hanselminutes.com/145/solid-principles-with-uncle-bob-robert-c-martin)
9. [The Principles of OOD (содержит ссылки на статьи по SOLID)](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)

**OOD Resources**

1. [Abstraction, Encapsulation, and Information Hiding](http://www.tonymarston.co.uk/php-mysql/abstraction.txt)
2. [Difference between Abstraction and Encapsulation](https://www.guru99.com/difference-between-abstraction-and-encapsulation.html#2)
3. [The DRY Principle Explained: Its Benefit and Cost with Examples](https://thevaluable.dev/dry-principle-explained/) [[Перевод](https://habr.com/ru/company/mailru/blog/349978/)]
4. [Why DRY? by Mark Seemann](https://blog.ploeh.dk/2014/08/07/why-dry/)
5. [The Wrong Abstraction](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)
6. [A Detailed Explanation of The KISS Principle in Software](https://thevaluable.dev/kiss-principle-explained/)
7. [Simple Made Easy — talk of Rich Hickey](https://www.infoq.com/presentations/Simple-Made-Easy/)
8. [The Art of Separation of Concerns](http://aspiringcraftsman.com/2008/01/03/art-of-separation-of-concerns/)
9. [Cross cutting concern example on SO](https://stackoverflow.com/questions/23700540/cross-cutting-concern-example)
10. [Cross cutting concern on Wiki](https://en.wikipedia.org/wiki/Cross-cutting_concern)
11. [Coarse-grained vs fine-grained on SO](https://stackoverflow.com/questions/3766845/coarse-grained-vs-fine-grained)

**Patterns checklist**

- [ ] What is the difference between structural, generative, and behavioral types of patterns?
- [ ] For each pattern, answer the questions:
    - What is the essence of the pattern?
    - What problems can be solved with the help of this pattern?
    - What are his shortcomings?
    - What are some examples of the use of this pattern?
    - What kind of pattern is this and why?
- [ ] Singleton
- [ ] Strategy
- [ ] Template method
- [ ] Factory, Factory Method, Abstract Factory
- [ ] Observer / mediator
- [ ] Facade
- [ ] Decorator
- [ ] Dependency injection
- [ ] Command
- [ ] Component
- [ ] What examples of the implementation of these patterns can be given in a functional language, or in a language where functions are objects of the first class, have closures, and do not have built-in implementation tools to express the classical OO approach?

**Patterns resources**

1. [Clojure Design Patterns](http://mishadoff.com/blog/clojure-design-patterns/)
2. [Refactoring guru: design patterns](https://refactoring.guru/ru/design-patterns)

**Вопросы для самопроверки прицнипам проектирования**

- [ ]  Inversion of Control
    - What is IoC?
    - What are the advantages of frameworks providing IoC over libraries?
    - What are the advantages of libraries without IoC over frameworks?
    - Can a module provide an interface that supports both approaches: with IoC and without IoC?
- [ ]  Dependency Injection
    - What is DI?
    - What are the alternatives to DI? What are the advantages and disadvantages of each alternative?
    - Can DI be implemented without IoC?
    - How does DI help to achieve the Separation of Concerns?
    - How are DI and Dependency Inversion Principle from SOLID related to each other?
- [ ]  What is Impedance Mismatch? What are the examples of Impedance Mismatch in different technologies? What are the most popular patterns of solutions?
- [ ]  What problems can be caused by premature optimization? How to solve troubles with performance while avoiding premature optimization?
- [ ]  What are the benefits of providing an API with different levels of abstraction?
- [ ]  Why do callbacks break composability?
- [ ]  Large Scale JS
    - What is the main idea of the proposed approach?
    - What patterns are used in this approach?
    - What is the role of events in this approach? Can the similar approach be implemented only with synchronous function invocations?
    - How does it help to achieve fault tolerance?
    - How can modules depend on each other?
- [ ]  Module API
    - What are the characteristics of a good module API?
    - How can we make an API hard to misuse? What are the benefits of this characteristic?
    - What are consistency and conceptual integrity properties of API? Why are the properties valuable?
    - How does writing use cases before writing code can help to achieve cleaner API?
    - What is the difference between extensibility by the module authors and module clients?
    - How can you explain the phrase "asymmetry of function should be reflected by asymmetry of form"?
    - How names used in your module API can reflect structure of your module and increase cohesion inside various parts of your contract?
    - What are the edge cases in the context of designing an API? Why is the implicit edge case handling preferred to explicit?
    - What is the rule "The best API is no API" about? What are the examples of breaking the rule?
- [ ]  How does modular programming help us to achieve better local reasoning while developing a module?
- [ ]  What are the benefits of declaring an explicit contract between a client and a person who implements a module?
- [ ]  What is the difference between abstraction by parameterization and abstraction by specification?

**Ресурсы принципов проектирования**

1. [How To Design Better JavaScript APIs](https://www.smashingmagazine.com/2012/10/designing-javascript-apis-usability/) (little bit opinionated post, don't consider as perfect guide)
2. [Library patterns Multiple levels of abstraction](http://tomasp.net/blog/2015/library-layers/)
3. [Library patterns Why frameworks are evil](http://tomasp.net/blog/2015/library-frameworks/)
4. [A quick intro to Dependency Injection: what it is, and when to use it](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/) [[Перевод](https://medium.com/@xufocoder/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-de1367295ba8)]
5. [Inversion of Control Containers and the Dependency Injection pattern](https://martinfowler.com/articles/injection.html)
6. [Dependency injection (from Wikipedia)](https://en.wikipedia.org/wiki/Dependency_injection)
7. [The Little Manual of API Design](https://people.mpi-inf.mpg.de/~jblanche/api-design.pdf)
8. [Modular Programming: Modules and Signatures](https://www.cs.cornell.edu/courses/cs3110/2013sp/lectures/lec07-modules/lec07.html)
9. [Patterns For Large-Scale JavaScript Application Architecture](https://addyosmani.com/largescalejavascript/)
10. [Создание архитектуры программы или как проектировать табуретку](https://habr.com/ru/post/276593/)
