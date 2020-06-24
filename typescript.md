# Typescript

### Books
1. [Effective TypeScript](https://www.amazon.com/Effective-TypeScript-Specific-Ways-Improve/dp/1492053740)

### Questions
* What are Type soundness and Type safety? Is there a difference between these concepts?
* What is structural typing? What are the alternatives? What are the advantages and disadvantages of this approach?
* In what cases does TS move away from the principles of structural typing and move on to nominative typing to determine the compatibility of types?
* What are declarations merging? How does it work in TS? What are the pros and cons? How are types combined for methods?
* Compatibility
  * Why TS considers compatible function type with fewer arguments
   `` `typescript
   ((a: number) => 0; assignable to (b: number, s: string) => 0;)
   `` ``
  * And how does this apply to the return result of functions?
  * Does TS Type soundness break because of this?
* What is Type Variance? What do Invariance, Covariance, Contravariance and Bivariance mean?
  * When does Covariance appear in TS? When is the Bivariance? When is the Contravariance?
  * If you pass a callback to the function that accepts another callback, will the parameters show Covariance or Contravariance (output by example yourself)?
  * If TS objects and classes were Invariant, how would this affect type safety and ease of development?
* What is Type Widening? How does this mechanism affect type safety in TS?
* fresh object literal type
  * What it is?
  * Why is excess property checking turned on for him in a special way?
  * Why does passing an object literal not directly to a function, but through intermediate variable assignment, increase the likelihood of an error in the program?
* What is a refinement? How does it work in the context of Discriminated Unions?
* Why can using generic variables in tags for Discriminated Unions make a program more bug-prone? When does it really lead to bugs, and when not?
* What is a Companion Object Pattern? How is Declaration Merging used to implement it?
* What is type inference? What are some common type inference problems? What types can TS output?
* What types of polymorphism does TS support and how to work with it?

### Resources

* [What is Type Soundness?](http://jschuster.org/blog/2017/03/21/what-is-type-soundness/)
* [Is there a difference between type safety and type soundness?](https://cs.stackexchange.com/questions/82155/is-there-a-difference-between-type-safety-and-type-soundness)
* [How can a statically typed language support duck typing?](https://softwareengineering.stackexchange.com/questions/252984/how-can-a-statically-typed-language-support-duck-typing)
* [Programming TypeScript by Boris Cherny. Chapter 6.](https://learning.oreilly.com/library/view/programming-typescript/9781492037644/ch06.html)
* [What are covariance and contravariance?](https://www.stephanboyer.com/post/132/what-are-covariance-and-contravariance)
* [TS FAQ. Why are function parameters bivariant?](https://github.com/Microsoft/TypeScript/wiki/FAQ#why-are-function-parameters-bivariant)
* [TS Handbook. Function Parameter Bivariance](https://www.typescriptlang.org/docs/handbook/type-compatibility.html#function-parameter-bivariance)
* [What the heck is polymorphism? (только главы до Row polymorphism  включительно)](https://dev.to/jvanbruegge/what-the-heck-is-polymorphism-nmh)
* [Discussion: Typed, modular macros for OCaml, thread about row polymorphism](https://news.ycombinator.com/item?id=13046210)
