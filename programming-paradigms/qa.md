Object-Oriented Programming refers to the programming paradigm defined using objects instead of only functions and methods. The objects contain data, called fields or attributes, and methods that provide the logic or supporting code. It provides capabilities such as inheritance, polymorphism, encapsulation, abstraction.

**What are the main features of object-oriented programming?**

_In this **OOPs interview question**, make sure you list the four main features_

- Inheritance
- Encapsulation
- Polymorphism
- Data Abstraction

**What are the advantages of Object-oriented programming?**

- Problems of any level of complexity can be supported by [o](https://www.upgrad.com/blog/is-python-an-object-oriented-language/)op programming.
- Highly complex problems can be handled by object-oriented programming
- It provides an efficient mechanism for code reuse using **inheritance** which reduces redundancy
- It provides a mechanism for hiding data
- It is based on a bottom-up approach
- It offers flexibility through polymorphism
- It improves maintainability of the code

**What is Structural programming?**

Structural programming refers to the traditional method of programming, which is based on functions. The overall program logic is divided into functions to provide a logical structure. It is based on a top-down approach. Structural programming is suitable for easy to moderately complex problems.

**What is a class?**

A class defines the template or the definition of an object. It is used for creating objects at run time. It provides the [data structure](https://www.upgrad.com/blog/data-structure-project-ideas-beginners/), provides initial values for the attributes, and methods that provide the logic for the intended behaviour of the object. The class does not consume memory at runtime. A class refers to a logical entity. E.g., a vehicle may be defined as a class.

**What do you mean by an object?**

An object refers to the run time instance created from the class during program execution. Objects can refer to real-world entities that have attributes or properties and methods to support the behaviour. Objects consume memory space when they are initialized.

**What is a constructor?**

A constructor method is used for initializing the objects. They are special types of methods and have the same name as the class.

**List the various types of constructors**

_Multiple types of constructors that are supported across multiple object-oriented programming languages are:_

- Default constructor
- Copy constructor
- Static constructor
- Private constructor
- Parameterized constructor

**What is a destructor?**

A destructor is a method used for freeing up the resources allocated to an object. This method is automatically invoked when an object is being destroyed.

**What is meant by a copy constructor?**

A copy constructor helps in cloning objects by replicating the values from one object into another object which belongs to the same class.

**Can you please highlight the difference between a class and a structure?**

A class means a user-defined template from which objects are created at runtime. A class is made up of methods that provide the logic for various behaviours supported by the objects.

A structure means a user-defined combination of attributes of various data types.

**Can you please explain the concept of inheritance with an example?**

Inheritance is a powerful feature of object-oriented programming which allows classes to inherit properties and methods from other classes. This helps improve code reuse.

For example, a base class represents a logical concept, such as a vehicle that may define only the common properties shared by all types of vehicles. However, child classes can inherit from this base class to define more specific types of classes such as a truck, a car, or a bus. In this case, the child classes will inherit the common attributes of the vehicle, and will be able to define attributes, method specific to its own.

**What are the limitations of inheritance?**

The inheritance requires more processing time for the programs as it has to navigate various classes during execution. Due to inheritance, the parent and child class are tightly coupled. When any changes are needed in the logic, it may require changes in both parent and child classes.

If the inheritance is not correctly implemented, it can lead to undesired results.

**What are the various types of inheritance?**

- Single
- Multiple
- Multi-level
- Hierarchical
- Hybrid

**What is the meaning of hierarchical inheritance?**

When multiple subclasses inherit a base class, it is called hierarchical inheritance.

**What is a subclass?**

The child class which inherits from another class is referred to as the subclass.

**Define a superclass?**

A superclass implies a class from which other classes inherit. e.g., the vehicle will be referred to as superclass of classes car, bus, or truck if they all inherited from the same superclass.

**What is meant by an interface?**

An interface allows a declaration of methods without providing a definition.

You cannot create objects from the interface. When a class implements an interface, it needs to implement the methods provided by the interface.

**What is polymorphism?**

Polymorphism is a significant feature of object-oriented programming. It means an ability to exist in multiple forms. A single interface can be implemented in multiple ways by providing various definitions.

**What is meant by static polymorphism?**

The static polymorphism or static binding allows us to link a function with objects during compilation. It can be implemented by method overloading of operator overloading.

**What is meant by dynamic polymorphism?**

A dynamic polymorphism or dynamic binding allows for a call to an overridden method at the run time.

**What is method overloading?**

The method overloading is a very useful feature of object-oriented programming in which multiple methods can have the same method name; however, they have different arguments. The call to the method is resolved based on the arguments.

**What is the meaning of method overriding?**

Method overriding allows the child class to redefine methods of parent class by applying its implementations. However, the method name, arguments, and return types remain the same.

**Can you explain what operator overloading is?**

The term operator overloading means that depending on the arguments passed, the operators’ behaviour can be changed. However, it works only for user-defined types.

**How do you explain the difference between overloading and overriding?**

Overloading a method means that multiple methods share the same method name but have different arguments. However, in the case of the overriding, the child class can redefine the implementation of a method by retaining the same arguments. Another difference is that the overloading is resolved at compile-time while overriding is resolved at run time.

**What do you know about encapsulation?**

Encapsulation is an important feature of object-oriented programming. It allows the binding of the data and the logic together in a single entity. It also allows the hiding of data.

**What is meant by data abstraction?**

The data abstraction refers to the ability of object-oriented programming that allows hiding the implementation details of logic yet allows for access to only important information.

**How can data abstraction be accomplished?**

Data abstraction can be accomplished through either an abstract class or an abstract method.

**What is meant by abstract class?**

An abstract class is made of abstract methods. The abstract methods are only declared, however, not implemented. When a subclass needs to use the methods, it needs to implement those methods.

**Can you please elaborate on ‘access specifiers’?**

Access specifiers are special keywords that control the accessibility of methods or classes etc. They are also called access modifiers and are used to achieve the encapsulation. e.g., the keywords public, private, and protected are some examples of access specifiers.

**How do you create an instance of an abstract class?**

You cannot create an instance of an abstract class since it lacks implementation logic in its methods. You first need to create a subclass that implements all the methods before an object can be initialized.

**Distinguish between data abstraction and encapsulation.**

Data abstraction is the ability to hide unwanted information.

The encapsulation refers to the ability to hide the data as well as the method together.

**What are the differences between interfaces and abstract classes?**

An abstract class can support both abstract and non-abstract methods. However, the interface allows only abstract methods.

In the case of an abstract class, both final and non-final variables are supported. However, the interface has variables that are, by default, defined as final.

The abstract class can have private, and public attributes, but interfaces have attributes as public by default.

**What is meant by an exception?**

An exception is an event raised during a program execution caused by undesirable input or a condition that prevents further processing. An exception causes an interruption in the program’s normal execution and must be handled via exception handling logic to avoid the program’s termination.

**Define exception handling**

Exception handling refers to the mechanism used for handling the exceptions raised during program execution. It allows for the graceful handling of undesirable results.

**Is an error basically the same as an exception?**

An error means a problem that the program should not catch while the exception implies a condition that should be caught by the program.

**What is a try-catch block?**

A try-catch block is used for exception handling. The set of statements that may cause a potential error are enclosed in a try block. When an exception is raised, it is caught by the catch block. The logic to handle an exception is placed inside the catch block.

**What is a finally block?**

A ‘finally’ block is used for executing essential statements such as to free the memory, close files, or database connections, even if an exception occurs. The finally block always runs.

**Should you always use Object-oriented programming? Are there any limitations of Object-oriented programming?**

Though object-oriented programming offers many advantages, it has some disadvantages too. First of all, it has a steep learning curve compared to procedural programming. It may take a while to get used to thinking and program in terms of objects for many people. Secondly, it may take more experience to design a program in terms of objects. Using OOPs concepts for smaller programming tasks may not be efficient.

**What are the advantages and disadvantages of object oriented programming?**

- **Improved software development productivity:** OO programming is modular, as it provides separation of duties in object-based program development. It is also extensible, as objects can be extended to include new attributes and behaviors. Objects can also be reused within an across applications. Because of these three factors; extensibility, modularity, and reusability.
- **Faster development:** Reuse enables faster development. Object-oriented programming languages come with rich libraries of objects, and code developed during projects is also reusable in future projects.
- **Lower cost of development:** The reuse of software also lowers the cost of development. Typically, more effort is put into the OO analysis and design, which lowers the overall cost of development.
- **Higher-quality software:** Faster development of software and lower cost of development allows more time and resources to be used in the verification of the software. Although quality is dependent upon the experience of the teams, OO programming tends to result in higher-quality software

Other **OOP disadvantages** are:

- **Steep learning curve:** The thought process involved in OO programming may not be natural for some people, and it will take the time to get used to it.
- **The complexity of creating programs:** it is very complex to create programs based on the interaction of objects. Some of the key programming techniques, such as inheritance and polymorphism, can be a big challenging to comprehend initially.

**OOP vs FP**

- **OOP Pros**
  - OOP is so popular because it allows keeping things secure from unwanted external use. It hides variables within the class and thus prevents outside access. Besides that, OOP allows for modularity (possibility to separate the functionality of a program into independent modules) and the management of shared states.
  - Objects can be easily reused in another application. It is easy to create new objects for the same class and it is easy to maintain and alter the code.
  - OOP has memory management. It offers a great benefit when it comes to creating large programs since it allows for easily dividing things into smaller parts and helps to distinguish the components that need to be executed in a certain way.
- **OOP Cons**
  - OOP is not reusable. Since some functions depend on the class that uses them, they are difficult to use with another class. In addition to that, it is less efficient and harder to deal with. Many object-oriented programs are also made to model massive architectures and can be complicated.

**Functional Programming Pros and Cons**

**FP Pros**

- FP offers advantages like lazy evaluation, bug-free code, nested functions, parallel programming. It uses a more declarative approach that concentrates on what needs to be done and less on how to do it, with an emphasis on efficiency and optimization.
- In functional programming, it’s much easier to know what changes were made since the object itself is now a new object with a different name. It’s effective when you have a fixed set of operations, and as your code evolves, you add new operations on existing things.
- It works well when boundaries are either not required or are already predefined. It’s most beneficial in situations where the state is not a factor and there’s little to no involvement with variable data.
- In functional programming, it’s easier to simulate real-world processes than objects. Its mathematical origins make it suitable for cases that require calculations or anything that includes transformation and processing. OOP in such cases will be inefficient.

**FP Cons**

- FP is all about data manipulation and takes a different mindset to write code. Though it’s easy to think in object-oriented terms, converting a real-world scenario into just will require more mental effort.
- Since FP is more difficult to learn, there are fewer people who program this way and, consequently, there is naturally less information on the topic.
