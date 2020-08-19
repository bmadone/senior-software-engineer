- What is TypeScript? What is it for and what problems does it solve?
- Tell about the following types of typing, their features, pros and cons:
    - weak / strong;
    - static / dynamic;
    - explicit / implicit;
    - structural / nominative;
- What types of typing are used in JavaScript and TypeScript?
- How and for what purposes are the data types listed below used?
    - Boolean
    - Number
    - String
    - Null and Undefined
    - Object
    - Array
    - Tuple
    - Enum
    - Any
    - Void
    - Never
    - Unknown
- What are type assertions used for? Why avoid them?
- What are the interfaces for?
- What is Type Aliases? Why do we need it? How do they differ from interfaces?
- What does `?` Do after an interface property name or function argument?
    - What is the difference between `x ?: number` and` x: number | undefined`?
- Why do you need the postfix `!`? Why should you avoid it?
- What interfaces can be inherited from? What are the restrictions imposed by inheritance from a class?
- What are the ways to type static-side class and instance-side class?
- Can a class simultaneously implement a set of interfaces and inherit from another class?
- What are the purposes of class property modifiers?
- What is the difference between abstract classes and ordinary classes and interfaces?
- Is it possible to declare the type of the method in the interface so that it returns the context of its call?

    ```jsx
    interface ISomething { getThis(): // указать тип
    }
    class Something implements ISomething { public getThis() { return this; }
    }
    ```

- What are Hybrid Types used for?
- What are Index types used for?
    - What is the `keyof` operator for?
- What are Mapped types for? How do I create my own Mapped type?
- What are generics for?
    - What are the built-in generic types?
    - How to limit the possible values ​​of a type variable?
    - How to restrict the possible values ​​of a type variable to values ​​of another type variable?
    - Can a default value be specified for a type variable?
    - Correct the typing of the `filterBy` function so that it:
        1. the first argument took an array of any objects;
        2. the second is the name of the field by which the filtering is performed;
        3. the third is the value that the field should contain;
        4. returned the type of the first argument (the original array).

        ```jsx
        // original function: function filterBy(input: Object[], propName: string, propValue: any): Object[] { return input.filter(item => item[propName] === propValue); }
        ```

        ```jsx
        // what should happen interface IEmployee { name: string; age: number; position: 'Programmer' | 'Accountant' | 'Designer'; } const employees: IEmployee[] = [ { name: 'Mikle', age: 20, position: 'Programmer' }, { name: 'Jordan', age: 25, position: 'Designer' }, { name: 'Stive', age: 34, position: 'Accountant' }, { name: 'Tom', age: 19, position: 'Programmer'}, { name: 'Bob', age: 43, position: 'Programmer'}, { name: 'Mikle', age: 19, position: 'Programmer'}, { name: 'Bob', age: 27, position: 'Designer'}, ];
        filterBy(employees, 'position', 'Programmer'); // return IEmployee[]
        filterBy(employees, 'surname', 'Cook'); // error, type IEmployee does not contain 'surname'
        filterBy(employees, 'position', 'Tester'); // error, field 'position' can't contain 'Tester',
        ```

    - Type the class `List` so that:
             1. The constructor of the class accepted an array of objects with the required field `id`;
             2. The `addItem` method allowed adding only an object with a constructor argument type;
             3. The `getList` method returned an array of objects with the type of the constructor argument;
    
         Original class

        ```jsx
        class List { private list; constructor(list) { this.list = list; } addItem(item) { this.list.push(item); } getList() { return this.list; } }
        ```

        // What should turn out

        ```jsx
        interface IGuest { login: string; password: string; } 
        const guests: IGuest[] = [ { login: 'guest', password: '123', }, { login: 'user', password: '123', } ]; 
        const guestsList = new List<IGuest>(guests); // ошибка, в типе IGuest отсутствует поле id interface IUser { id: number; login: string; password: string; } 
        const users: IUser[] = [ { id: 1, login: 'guest', password: '123', }, { id: 2, login: 'user', password: '123', }, { id: 3, login: 'author', password: '123', } ]; 
        const usersList = new List<IUser>(users); // ok usersList.addItem({ login: 'guest', password: '123', }); // ошибка, отсутствует поле id usersList.addItem({ id: 3, login: 'admin', }); // ошибка, отсутствует поле password usersList.addItem({ id: 5, login: 'guest', password: '123', }); // ok const usersArray = usersList.getList(); // IUser[];
        ```

    - What are the rules for deriving the types of generic arguments when calling functions in the following cases:
              - if the generic argument is explicitly passed when calling the function;
              - if the generic argument is not passed and this argument is used to type the function argument;
              - if the generic argument is not passed and this argument is used to type the value returned by the function;
          - How can you use generalizations in react components?
      - Union and intersection types
          - What are they for?
          - How to use?
      - What are Type Guards? What are they needed for?
      - How the Basic Type Guards work:
          - operator `in`
          - `typeof`
          - `instanceof`
              - In what cases, when inheriting from `Error`, instanceof` can return an incorrect result? How can this problem be solved?
          - comparison `== / ===`
          - negation `!` and double negation `!!`
      - How to declare your Type Guard?
      - What are Assertion Functions and what are they for?
      - What is a Discriminated union?
          - What type of discriminant can be?
          - Can you use a discriminant check as a Type Guard?
          - What is exhaustiveness checking? Why is this needed? How can this be achieved?
      - What is Branding and Flavoring?
          - What are they used for?
          - What is the difference between them?
          - What problems can arise when using branding and flavoring for Record keys?
          - What are the pros and cons of these approaches and when should each of them be applied?
### **Links**

- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/basic-types.html)
- [TypeScript FAQ](https://github.com/microsoft/TypeScript/wiki/FAQ)
- [Ликбез по типизации в языках программирования](https://habr.com/ru/post/161205/)
- [Зачем использовать статические типы в JavaScript?](https://habr.com/ru/post/326304/)
- [Flavoring: Flexible Nominal Typing for TypeScript](https://spin.atomicobject.com/2018/01/15/typescript-flexible-nominal-typing/)
- [Номинативная типизация в TypeScript или как защитить свой интерфейс от чужих идентификаторов](https://habr.com/ru/post/446768/)

- What is function overloading? What are the ways to implement it?
- How to typeset a class constructor?
    - Can a constructor overload for a class be typed?
- What is const assertion?
    - What is it for?
    - What are the restrictions?
    - There is the following code: Which of the last two lines will cause an error and which will not? Why?

        `` `jsx
        let names = ['Mary', 'David'];
        let group = {participants: names, ageRestriction: 18,
        } as const;
        group.participants.push ('Henry');
        group.ageRestriction = 12;
        ``,

- How to create a new type based on the existing one, with the addition of new properties?
    - Practical task: Based on the existing types `Avenger`,` Head`, `Dead` and the interface` IPersonalInformation`, create a new type of object `SurvivedAvengers <T>`, which must satisfy the following conditions:
        - T must be compatible with the Avenger type; *
        - SurvivedAvengers <T> must contain keys of type T except for keys of type Dead; *
        - SurvivedAvengers <T> must contain keys of type Head; *
        - SurvivedAvengers <T> must not contain any other keys; *
        - in SurvivedAvengers <T>, each key must correspond to the value of the IPersonalInformation interface; 
        
        *
            `` `jsx
            type Avenger = "Thor" | "Hawkeye" | "Captain America" ​​| "Iron Man" | "Dr. Strange" | "Nick Fury";
            type Head = "Nick Fury";
            type Dead = "Iron Man";
            interface PersonalInformation {age: number; name: string; superpower: any;
            };
            Example:
            const personalInformation: PersonalInformation = {age: 25; name: 'NameOfAvenger', superpower: 'SuperpowerOfAvenger'};
            const survivedAvengers: SurvivedAvengers <'Thor' | 'Hawkeye' | 'Iron Man'> = {'Thor': personalInformation, 'Hawkeye': personalInformation, 'Nick Fury': personalInformation};
            ``,
            
        - Now make it so that in the object `survivedAvengers` the keys of type` Head` are optional.
        - Now make it so that in the object `survivedAvengers` the keys of type` Head` are optional, except for keys passed to the generic, i.e. common keys from `Head` and` T` must be required, and all other keys from `Head` must be optional.
- What is the purpose of the types listed below?
    - `Partial <T>`
    - `Readonly <T>`
    - `Required <T>`
    - `Record <T, U>`
    - `Pick <T, U>`
    - `Omit <T, K>`
    - `Exclude <T, U>`
    - `Extract <T, U>`
    - `NonNullable <T>`
    - `ReturnType <T>`
    - `Parameters <T>`
    - `InstanceType <T>`
    - `ThisType <T>`
- What are Conditional Types for?
    - How does distributivity manifest itself in Conditional Types?
    - How to remove a composite type from a union type using Conditional Types?
    - Can Conditional Types be used in conjunction with Mapped Types?
    - What is `infer` for? Is it allowed to use `infer` on non-Conditional Types?
- Is it possible to declare recursive type Aliases in TypeScript?

### **Links**

- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/advanced-types.html)
- [How 2 TypeScript: Serious business with TypeScript's infer keyword](https://dev.to/miracleblue/how-2-typescript-serious-business-with-typescripts-infer-keyword-40i5)
- [Conditional Types in TypeScript](https://mariusschulz.com/blog/conditional-types-in-typescript)
