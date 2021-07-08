# Architecture

## Questions

*  Inversion of Control
    - What is IoC?
*  Dependency Injection
    - What is DI?
    - What are the alternatives to DI? What are the advantages and disadvantages of each alternative?
    - Can DI be implemented without IoC?
    - How does DI help to achieve the Separation of Concerns?
    - How are DI and Dependency Inversion Principle from SOLID related to each other?
*  What problems can be caused by premature optimization? How to solve troubles with performance while avoiding premature optimization?
*  What are the benefits of providing an API with different levels of abstraction?
*  Why do callbacks break composability?
*  Module API
    - What are the characteristics of a good module API?
    - How can we make an API hard to misuse? What are the benefits of this characteristic?
    - What are consistency and conceptual integrity properties of API? Why are the properties valuable?
    - How does writing use cases before writing code can help to achieve cleaner API?
    - What is the difference between extensibility by the module authors and module clients?
    - How can you explain the phrase "asymmetry of function should be reflected by asymmetry of form"?
    - How names used in your module API can reflect structure of your module and increase cohesion inside various parts of your contract?
    - What are the edge cases in the context of designing an API? Why is the implicit edge case handling preferred to explicit?
    - What is the rule "The best API is no API" about? What are the examples of breaking the rule?
*  What is the difference between abstraction by parameterization and abstraction by specification?

## Links
* [Library patterns. Multiple levels of abstraction](http://tomasp.net/blog/2015/library-layers/)
* [Library patterns. Why frameworks are evil](http://tomasp.net/blog/2015/library-frameworks/)
* [A quick intro to Dependency Injection: what it is, and when to use it](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/)
* [Inversion of Control Containers and the Dependency Injection pattern](https://martinfowler.com/articles/injection.html)
* [Dependency injection (from Wikipedia)](https://en.wikipedia.org/wiki/Dependency_injection)
* [The Little Manual of API Design](https://people.mpi-inf.mpg.de/~jblanche/api-design.pdf)
* [Modular Programming: Modules and Signatures](https://www.cs.cornell.edu/courses/cs3110/2013sp/lectures/lec07-modules/lec07.html)
* [Solid book](https://ota-solid.now.sh/)
* [Premature optimization](https://optimization.guide/)
