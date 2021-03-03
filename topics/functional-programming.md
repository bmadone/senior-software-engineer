## Functional programming

### Questions

* What is arity? How to get function arity in JS?
* What is first-class citizen? What is it in JS?
* What are the consequences of the fact that in JS functions are also first-class citizen?
* What is a higher order function?
* Control flow
    - What?
    - How does it affect code complexity?
    - What are the features of control flow in programs written in a functional paradigm?
* Partial use of functions and currying
    - When can partial application of functions be useful?
    - When can currying be useful?
    - What are their differences?
    - What is their influence on the arity of functions?
* Function Composition
    - What?
    - What is it used for?
    - What is a `pipe`?
    - How to implement the `compose` function?
* Point-free style
    - What?
    - What advantages can give?
    - What could be the disadvantages?
* What are side effects? How are they harmful and how are they useful?
* What are pure functions? What are dirty functions? What are the advantages of some over others?
* Can a dirty call come from a pure function? If so, what does it mean?
* How to limit the effect of "dirty functions" on the system?
* What is idempotency? What is the difference between software and mathematical idempotency?
* What is link transparency? Is referential transparency of a function call expression a sufficient sign of the purity of this function?
* Immutability
    - What?
    - Are objects contained in variables declared with `const` immutable?
    - What are the advantages of immune data structures?
    - What is structural sharing and what problems does it solve?
* Recursion
    - What?
    - What are the advantages and disadvantages of the application?
    - What is tail call optimization? Is it supported in JS?
* Study the book [Professor Frisby's Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide) by Franklin Frisby (chapters 8-12 included)
* Explore the book [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) by Kyle Simpson (chapters 9-11, plus additions).
* How to implement the functionality of objects through closures and vice versa? What are the advantages of each method?
* What are categories? What are morphisms?
* What is isomorphism?
* What is a functor?
* How can I avoid unnecessary passes through the array?
* What is lazy computing? What are the advantages and disadvantages of lazy computing?
* What is transduction? What problems can be solved with this tool?
* What is a pointed functor?
* What are monads? What are they used for? What do the monads below do?
* What is associativity?
* What is an applicative functor? What is the scope of its application?
* What do the following utilities do?
    - `identity`
    - `partial` /` partialRight`
    - `prop`
    - `curry` /` uncurry`
    - `cond`
    - `flatMap` /` chain`
* Immutability and state
    - Can the state of the program be immutable?
    - What is the problem of storing the state of the program?
    - Why does a mutable state make it difficult to comply with the guarantee of invariants throughout the program life cycle?
    - Why does mutability impose additional requirements on the order of functions? How can this be avoided?
    - Describe the following state models. How can they be graded according to the degree of danger?
        - Invisible to the client mutable state
        - Encapsulated mutable state
        - Invisible programmer mutable state
        - Two-phase life cycle
        - A mutable state shared between several processes
        - Lack of mutable state
        - Unencapsulated mutable state
        - Managed mutable state
        - Monotonous variable state

### Links
1. [Robert C Martin - Functional Programming; What? Why? When?](https://www.youtube.com/watch?v=7Zlp9rKHGD4)
1. [Functional Programming Design Patterns](https://www.youtube.com/watch?v=E8I19uA-wGY)
