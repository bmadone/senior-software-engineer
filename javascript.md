##  Data 

- What data types are there in JS?
- Which types in JS are mutable and which are not?
- What does a reference to a variable mean?
- What is `NaN`? How can I check if a variable is `NaN`?
- What does it mean to create a variable through a constructor or through a literal?
- When should you use dot notation when accessing an object property, and when through a string in square brackets?
- What happens if you try to get a property that does not exist in an object?
- What does `hasOwnProperty` do?
- When to use `null` and when to use` undefined`?
- What are the ways to create global variables?
- What is the `use strict` directive for?

## Expressions

- What are expressions and instructions? What are the differences between them?
- What is the difference between `var`,` let`, `const`? Why use `const` might be preferable?
- What is a ternary operator?
- What does the `for..in` operator do? What are the special features of using this operator with arrays?
- How to safely check that the variable exists (was declared) and not catch a ReferenceError?


## Arrays

- Ways to create arrays (literal, constructor, factory methods `Array.from ()` and `Array.of ()`);
- Removing an element from an array (what are the ways and what are the features);
- The `length` property of an array
    - What value will the property `length` of array` a` have and why:

      `  const a = [1, 2, 3];
        a [10] = 4;`

        - What happens if you reassign a new value?
        - Does `length` have an effect on deleting an element in the middle of the array? Which ways to remove items affect the length and which do not?
- How to check that the variable contains an array?
- What they do, how and when to use the following methods:
    - `reduce`
    - `sort`
    - `filter`
    - `map`
    - `forEach`
    - `some`
    - `every`


## Functions

- What are the 4 function call templates that set the context for the execution of this function?
    - How does the `use strict` directive affect` this` inside a function?
- What's the simplest pattern to make a function easier to read when it has a huge number of arguments?
- How to get all the arguments of the function (including those that are not declared, but were still passed)?
- What is recursion? When is it convenient to use it?
- What are closures, and when can they be useful? How can we store state with a closure, and what can this state be used for?
- How to implement the `bind` function?
- To solve the following problem: let us have an array of links, and our task is to make sure that when you click on each, its ordinal number is displayed. The first solution that comes to mind looks like this: In fact, it turns out that when you click on any link, the same number is displayed - the value of `links.length`. Why is this happening and how to fix this muck?

   ` for (var i = 0; i <links.length; i ++) {links [i] .onclick = function () {alert (i); }
    }`

- What is callback (callback function)? When are they usually used?
- What is currying?
- What is partial application?
- What is memoization?

## Prototypes

- What is a constructor function? How to create them and how to use them?
- What is a prototype? What opportunities does it have / gives?
- Why is it better to store object methods in the prototype and not in the object itself?
- Is it possible to create a function instance through the constructor? And if so, how, and if not, what interface would you implement for this task?
- How to create an object that doesn't inherit from anything?
- What 3 (at least) ways are there to be inherited in JavaScript? What are the differences and nuances?
- How to call the overridden method of the parent in the overridden method of the inheriting class? Example pseudocode:

    class Person method getFullName () return this.name + this.surname
    class Employee extends Person method getFullName () return super () + this.position

- What are the ways to permanently bind a class method to its instance (so that `this` is always the current instance of the class)?

## Objects

- What are getters and setters? How can I use them natively in JS?
- Object property descriptors: what is it and what can you do?
- Casting objects to primitives: when does it happen and how does it work?
 - How to make it possible to add two objects?

`     const a = {x: 3};
     const b = {x: 5};
     ...
     console.log (a + b); // 8
     `

 - How to make the following expression return `true`?

     `(c == 1 && c == 2 && c == 3)`

## Arrays

- Is it possible to interrupt traversal of elements in the `forEach` method?
- Can you use the `indexOf` method to determine the position of the subarray` [3, 4]` in the array` [1, 2, [3, 4], 5] `?
- How to convert a string to an array? Can array methods be applied to strings?

## Functions

- What is the "floating" of variable declarations, and in what case do functions appear here?
- Does the `use strict` directive affect bubbling? How can we avoid floating up variables?
- What is IIFE (immediately invoked function expression)? What are the ways to write IIFE and why does it work like that?
- How do I keep the parent context when called immediately invoked function expression?
- How to use standard array methods on fake arrays (for example, call `map` on` arguments`) and why does it work?

## Regular Expressions

- Why do we need regular expressions?
- What methods do regular expression instances in JS have?
- What methods do strings have that allow you to work with regular expressions?
- What are flags in regular expressions? Tell about flags of globality, case insensitivity, multi-line.
- How do the methods of specifying the quantity (quantifiers) `*`, `+`, `{3}` work?
- What do the characters `[]` and `[^]`, `.`,`? `,` ^ `,` $ `,` | `Mean in regular expressions?
- What are greedy and lazy quantifiers?
- How to use basic placeholders `\ W`,` \ w`, `\ D`,` \ d`, `\ S`,` \ s`, `\ B`,` \ b`?
- How does `\ b` work for the beginning of a line and for the end of a line? Why does the regular expression `\ babc \ b` work for the string` abc`, but the regular expression `\ b \. \. \ B` does not work for the string` ..`?
- When to use the escape character `\`?
- Why do we need groups? How to work with them?
- Can I create nested groups?
- What do `$ 1`,` $ 2`, etc. mean? in text editors in a replacement box if the search supports regex?
- How to make an unmemorable group (a group whose entry will not be returned when matching a string to a regular expression)?
- How to use the group value in the regex itself?
- Solve tasks:
    - Write a regular expression to translate Function Expression into Function Declaration.
    - Write a regular expression to translate Function Declaration into Function Expression.
    - Write a regular expression to search for all Telegram commands in a message (examples: `/ help`,` / start`, `/ active_orders`,` / order123`). Take into account that there can be several commands in a substring.
    
    
## Promises

- What is Promise? What is it for?
- How to create a Promise?
    - What is the difference when creating promises with a constructor and with a factory?
- Methods `then` and `catch`
    - What are they doing?
    - What is promise chaining?
    - What can their callbacks return, and how will this affect the state of the promise returned by the `then` or `catch` data?
- What is the difference between 
`then (resolveHandler).catch (rejectHandler)` and `then(resolveHandler, rejectHandler)`?
- Can a promise be canceled?
- Tell about the methods:
    - `Promise.resolve`
    - `Promise.reject`
    - `Promise.all`
    - `Promise.race`
- What are the advantages and disadvantages of callbacks and promises?
- What meaning and state will the next promise have and why:

    `const promise = new Promise ((resolve, reject) => {resolve (0); reject (1); resolve (2);});`
