# Reading Notes

This is a website where i can keep track of my observations and questions from the reading assignments throughout Code 401 course.

## Code 401 - Advanced Software Development

## Introduction
Welcome to **Reading Notes**, a website designed to help you keep track of your observations and questions from the reading assignments throughout the Code 401 course. In this advanced software development course, you will delve deeper into the world of coding and gain valuable knowledge and skills.


## Benefits

- **Organizing**
- **Observations**
- **Questions**
- **Accessibility**

> "a way to document and highlight my new knowledge"

I have finished the "Introduction to SQL" prep work, and i learned a lot about SQL Queries and Database management!
Here is a screen shot to confirm finishing it:
![](./DB.png)


<!--  -->


# Prep: Practice in the Terminal

## Bash Command Line Tutorials

 My learnings and observations from completing the Bash Command Line Tutorials :


1. The Command Line 
- What is it and how does it work.

2. Basic Navigation
- An introduction to the directory system 

3. More About Files 
- Find out some interesting characteristics of files and directories.

4. File Manipulation 
- How to make, remove, rename, copy, and move files and directories (it was like a good review to me).

5. Cheat Sheet 
- A quick reference for the main points covered in this tutorial.

--------------------------------------------------

## Data Structures and Algorithms

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?

When deciding which data structure to use, it's crucial to consider the efficiency of operations required by the problem, such as insertion, deletion, or search, to ensure optimal performance, also for example if we need a fixed size or not as arrays have fixed size but linked list doesn't and so on.

2. How can we ensure that we’ll avoid an infinite recursive call stack?
To avoid an infinite recursive call stack, we can implement proper base cases in our recursive function, ensuring that the recursion stops at a specific condition. 


--------------------------------------------------




## The Growth Mindset


The growth mindset is emphasized in the article "Upgrade your technical skills with deliberate practice," highlighting the importance of deliberate practice, breaking down skills, and planning for learning and practice. Carol Dweck's TEDxNorrkoping talk on "The power of believing that you can improve" emphasizes the significance of adopting a growth mindset, believing in one's ability to learn and overcome challenges in programming and development.

In terms of emotional intelligence, the self-assessment tool indicates that I have a good overall level of emotional intelligence. I demonstrate self-awareness, self-regulation, and social awareness, with a solid foundation in understanding my emotions, admitting mistakes, and showing empathy. Although there are areas to improve, such as managing biases and negative emotions at work, overall, my results indicate progress and the need to continue working on growth.

Regarding the bias self-assessment, my score falls between 75 and 99, indicating some progress in addressing unconscious bias while recognizing the need for further growth. To continue improving, I should prioritize self-care, challenge myself with new perspectives, and actively seek out diverse opinions to expand my understanding and mitigate bias.

--------------------------------------------------
## Engineering Readings

What’s the one thing I bring to this career (and a potential employer) that nobody else can?

The one thing that sets me apart and makes me a valuable asset in this career and to potential employers is my work ethic and ambition.
I work hard and put all my efforts to achieve my goals, and I always try to focus on solutions instead of problems.




What are 3 things I’ll start doing to “un-stick” myself whenever I get stuck on a tough piece of code, logic, or feature?

Whenever I get stuck on a tough piece of code, I try to do these steps:

1. I give myself a short break if I feel tired and can't focus, its important to stay calm and not be stressed

2. I like to trace the code line by line, sometimes I use a pen and paper if there's a need for it, and it's very helpful

3. searching for potential solutions on the internet, I use different resources like StackOverflow

--------------------------------------------------


## Class 1 - Readings: Exception Handling

1. Name one major benefit of being able to trace the call stack?

One major benefit of being able to trace the call stack during debugging is that it helps in understanding the sequence of program execution. 
This will help to find errors.

2. If you could use try/catch in your day to day life, name an exception you’d like to ‘catch’ and handle?

If I could use try/catch in my day-to-day life, an exception I'd like to 'catch' and the handle is the "DelayException." This would be an exception that occurs when I'm late for something. By catching this exception, I could implement an alternative solution or plan to be on time.

3.From an efficiency standpoint, are there downsides to try/catch blocks?
When an exception is thrown, the program flow is interrupted, and the runtime environment searches for an appropriate catch block to handle the exception which may affect program speed or performance. 
so we should only use it when its important.

4. Describe how you explain the .Net approach to exception handling to a non technical friend?

To explain the .NET approach to exception handling to a non-technical friend, I can give him an example of a situation when we need an alternative solution. 
such as if you can't find a specific product on the market, try to find a similar one from another brand.


--------------------------------------------------

## Class 2 - Readings: Unit Testing and Documentation

1. Three ways in which Unit Testing improves your codebase and productivity are:

- Detecting Bugs Early

- Facilitating Refactoring

- Enhancing Productivity and making the testing faster by automating it.

2. To write a unit test for a household task such as putting away laundry:
-  Write the function that represents the task, such as "puttingAwayLaundry()".

- Write test cases for different scenarios. we might have test cases for different types of clothes or colors.

- Invoke the "putAwayLaundry()" method with the test inputs.

- Evaluate the testing result is the same as the expected one.

 

3. Three reasons a quality README is just as important as quality code are:

- It will help other developers who want to understand the code if they want to use it, just like documentation. 

- It will make collaboration easier between the team.
- It will guide you on how to deal with the code so you can run it on your computer




4. Four crucial elements to include when writing a README for co-developers are:

1. An overview about the project

2. How to install and set up the project

3.how to use the project with an example use cases. 

4. Any other guidelines

--------------------------------------------------

## Class 3 - Readings: File Manipulation / System.IO


This topic is important because as developers it allows us to do many operations on files such as creating, reading, appending, and writing to the file.

In C#, "File Manipulation/System.IO" refers to the collection of classes and methods made available by the System.IO namespace.
It provides many operations for handling files.

### I learned about many classes like: 

File I/O:

- File class
- StreamReader and StreamWriter classes


Stream I/O:

- FileStream class

- StreamReader and StreamWriter classes

- BinaryReader and BinaryWriter

## Things I want to know more about

I want to know in what kind of projects I will need to work with files, so i want to see real examples.

--------------------------------------------------

## Class 4 - Readings: Classes & Memory Management

### Constructor

1. What’s the difference between a static and an instance constructor?

In c#,  "static constructor " is used to initialize static members of a class, It is declared using the static keyword and does not take any parameters.

On the other hand, "instance constructor" is used to create an instance of a class. It is called when a new instance of the class is created using the "new" keyword and it takes parameters.


2. How does the use of a static constructor differ from setting properties/values?

A static constructor is used to initialize static members, while setting properties/values is a way to initialize instance members.

Also, we can set properties/values many times on different instances, not only one time

### Stack and Heap

3. Knowing what you now know about the stack and the heap, how might you rethink the way you did projects in previous courses, to make more effecient use of memory?

I think I would use the stalk to keep track of the methods execution, and I will be more careful when I use Value Types and Reference Types
as using Reference Types in the wrong way might affect the performance.
This is what I'm thinking based on my understanding of the article, but of course, I'm excited to understand this topic more deeply so I can make more effecient use of memory

### Garbage Collector

4. Compare “Garbage Collection” in C# with the lifecycle of normal household items.

Every once in a while, we need to get rid of unused things in the house to keep it organized and clean. They were useful at a specific time, but now they are just taking up space!

Same as Garbage Collector in c#, it identifies and removes objects that are no longer being used, to free the memory.




--------------------------------------------------

## Class 5 - Readings: Linked Lists

##  Big O
Big O notation is a way to measure the efficiency of algorithms and data structures.
by big O we can analyze the performance based on the time complexity, space complexity, and the input size(n), for the best and the worst case scenarios

In this way, we can decide which is the best data structure or algorithm to use for the software.

## Linked lists
Linked lists are a data structure that has two types (singly and doubly).
linked lists have no fixed size and no index, and they don't require contiguous memory allocation, so it differs from arrays and it has their benefits of use.

Linked lists consist of nodes and pointers, where pointers are references to the next node in the SLL, and in DLL there are pointers for the next and previous nodes

we prefer to use Linked lists when we need flexibility for memory and we don't want a fixed size, but we don't prefer it when we need quick access for elements as it has linear complexity.

--------------------------------------------------

## Class 6 - Object Oriented Principles

### Inheritance

Inheritance enables you to create new classes that extend and modify the behavior defined in other classes.
Where the parent class is called also a base class, and the class that inherits those members is called a derived class.

To extend a class in C#, we use the : (colon) symbol.



### Abstract 

In c#, we can use the "abstract" keyword, which enables us to create classes and class members that are incomplete and must be implemented in a derived class.
As the abstract methods have no implementation, the method definition is followed by a semicolon instead of a block.


### Sealed

Also, we have "sealed"  keyword, which is used to prevent a class from being inherited or overridden.
As the sealed class can't be used as a base class, and it cannot be further derived from.
we prevent inheritance by adding "sealed" class
and we prevent overriding the method by adding the sealed keyword before the override keyword.


### Polymorphism


Polymorphism means "many-shaped", it allows override methods in derived classes that share a base class.
So when we create objects it will have different behaviors based on their actual types. just like a circle and rectangle from a class shape, every shape will have different behavior.

In C#, we can use the "virtual" keyword to declare a method or class member in a base class that can be overridden in derived classes.
It provides a mechanism for polymorphism and allows derived classes to have their own implementation of the virtual member.



### Hide base class members with new members (new)

Also, there is the "new" keyword, In case we want the derived class to have a member with the same name as a member in a base class; we can use "new" to hide the base class member.
It becomes before the return type of a class member that is being replaced.




--------------------------------------------------

## Class 7 - Interfaces

### Interfaces - define behavior for multiple types

**An interface in C# contains definition of a set of related functionalities that must be implemented by a non-abstract class. It allows for defining static methods with implementations and provides the option to include default implementations for its members.**

To create an interface, you use the "interface" keyword, and interface names begin with a capital "I".

By default, interface members are public, but you can explicitly specify accessibility modifiers such as public, protected, and so on.

**properties and methods in c# interfaces are public by default, and implicitly abstract**

In order to implement an interface member, the corresponding member in the implementing class must be public, non-static, and have the same name and signature as the interface member.


- An interface can define default implementations for some or all of its members. When a class implements the interface, it is not required to implement members that have default implementations.

- C# doesn't support multiple inheritance of classes. A class can only inherit from a single class, but it can implement multiple interfaces.





#### What is the problem that the interface solves?
The basic problem an interface is trying to solve is to separate how we use something from how it is implemented.

this means that if we have a Driver class it should be able to have a method Drive that can be used to drive any car, boat, or other kind of class that implements the IDriveable interface.




### Default interface members
Members with bodies allow the interface to provide a "default" implementation for classes that don't provide an overriding implementation


### Interface instances
An explicitly implemented member can't be accessed through a class instance, but only through an instance of the interface. In addition, default interface members can only be accessed through an instance of the interface.


--------------------------------------------------

## Class 8 - Collections & Enums


## Collections

In c#, collections are used to group related objects. There are two main ways to group objects: using arrays or using collections.

Collections offer more flexibility compared to arrays. They allow the group of objects to dynamically grow or shrink as needed. In some collections, you can assign a key to each object, making it easy to retrieve objects based on the key.

If your collection only contains elements of a single data type, you can use the classes in the System.Collections.Generic namespace. These generic collections ensure type safety, preventing the addition of objects of other data types. When retrieving an element from a generic collection, you don't need to determine its data type or convert it.

There are different kinds of collections available:

- System.Collections.Generic classes: These enforce strong typing and only allow the desired data type to be added.
- System.Collections.Concurrent classes: These are used in scenarios where multiple threads are accessing the collection concurrently.
- System.Collections classes: These store elements as objects of type Object without specific typing.

LINQ (Language-Integrated Query) can be used to perform queries on collections, making it easier to access and manipulate the data.

If you want to define your own custom collection, you can do so by implementing either the IEnumerable <T<T>> or IEnumerable interface.




## Enumeration Types

An enumeration type, also known as an enum type, is a (value type) that consists of a set of named constants with underlying integral numeric values. 
We can define an enumeration type by the "enum" keyword and specify the names of the enum members.

Enumeration types are useful when you want to represent a choice from a set or a combination of choices. 

In addition to representing mutually exclusive choices, enum types can also be used as bit flags. By using bitwise operations, you can combine multiple enum values into a single value to represent a combination of choices.

Using enumeration types provides several benefits, including improved code readability, type safety, and ease of maintenance. Enum members serve as self-descriptive constants, making the code more expressive and easier to understand.

enumeration types are helpful for defining sets of named constants with integral values, allowing for clearer and more structured representation of choices and combinations in your code.

--------------------------------------------------

## Class 9 - LINQ & Delegates

## Language Integrated Query (LINQ) (C#)

LINQ is a set of technologies that enables queries to be directly integrated into the C#.
With LINQ, developers don't need to use different query languages for various data sources like SQL databases, XML documents, and web services.
LINQ queries can be written in C# for SQL Server databases, XML documents, and any collection of objects that support IEnumerable or the generic IEnumerable<T<T>> interface. 

With LINQ, developers can write queries as first-class language constructs, similar to classes and methods.
We can use familiar operators and keywords to query strongly typed collections of objects. so we can perform filtering, ordering, and grouping operations on different data sources with minimal code. 


Query expressions can be compiled to expression trees or to delegates, depending on the type that the query is applied to. IEnumerable <T<T>> queries are compiled to delegates. IQueryable and IQueryable<T<T>> queries are compiled to expression trees.




## Introduction to LINQ Queries (C#)

A query is an expression that retrieves data from a data source. 

developers have had to learn a new query language for each type of data source for example, SQL for relational databases and XQuery for XML.

But LINQ simplifies this situation, As in a LINQ query, you are always working with objects. You use the same basic coding patterns to query and transform data in any format LINQ provides.


Three Parts of a Query Operation:

1. Obtain the data source.
2. Create the query.
3. Execute the query (for example in a foreach statement).

### Forcing Immediate Execution

Queries that involve aggregation functions like Count, Max, Average, and First, don't require an explicit foreach statement because the query itself internally utilizes foreach to produce a result. It's important to note that these queries return a single value rather than an IEnumerable collection. Basic LINQ Query Operations (C#)

In a LINQ query, the "from" clause comes first in order to introduce the data source and the range variable, The range variable is like the iteration variable in a foreach loop.

- Filtering (where)
- Ordering (order by)
- Grouping (group by)
- Joining (join)

--------------------------------------------------

## Class 10 - Stacks and Queues



### Stack 
**is a linear data structure that follows the Last-In-First-Out (LIFO) principle.** 

It consists of Nodes, where each Node references the next Node in the stack, but does not reference its previous one.

The stack supports two main operations:
1. Push: add an element to the top of the stack
2. Pop: removes the top element from the stack.

and we also have a peek to get the top value, and IsEmpty to check if it's empty.
The time complexity for all of them is O(1)

### Queue
 **It is another linear data structure that follows the First-In-First-Out (FIFO) principle.**

 The queue supports many operations: 
1. enqueue:  add an element to the rear (end) of the queue
2. dequeue:  remove the element at the front of the queue.

And same as the stack we have peek and IsEmpty


--------------------------------------------------

## Class 11 - Introduction to Databases and ERDs

1. **What is a Schema?**  
A schema in a database defines how data is organized within a relational database, such as tables.
Schemas provide a way to group related entities and manage access permissions.

    **Why do we use them?**  
It helps to build and manage databases, by organizing the database and managing access control.

     **What do they look like?**  
It looks like a diagram with many arrows that represent relations between entities


2. **What are the different types of Database Keys?**  

- **Primary Key**: a unique identifier for a row in a table. 
- **Foreign Key**:  it comes by having a relationship between two tables by referencing the primary key of the other table.

- **Composite Key**:  is used when a single column cannot uniquely identify a row. So it is a primary key that consists of multiple fields to create a unique identifier for a record.

  **How are they different? When do you use one over the others?**  
- primary key used when we have a unique identifier for each row in a table.
- foreign key used when we have relationships between tables 

- composite key used when a single column cannot uniquely identify a record



3. **What are Relationships in a relational database?**  
Relationships define the relations between tables in a relational database.

   **What is a 1:1 relationship?**  
It's when each record in one table is related to exactly one record in another table.

    **What is a Many: Many relationship?**  
when multiple records in one table are related to multiple records in another table. When we have many:many relationships we need a junction table to associate the related records between the two tables.

   **What is a 1:Many or Many:1 relationship?**  
when each record in one table can be related to multiple records in another table, but each record in the related table is related to only one record in the first table. 


--------------------------------------------------

## Class 12 - Entity Framework and APIs

### Entity Framework Core

Entity Framework Core is an object-relational mapping (ORM) framework for .NET, that allows developers to work with databases using object-oriented concepts.

It simplifies database operations by enabling developers to interact with the database using familiar things such as classes, objects, and LINQ (Language-Integrated Query). 
Entity Framework Core supports various database providers and allows for the creation, retrieval, modification, and deletion of data without the need to write complex SQL queries manually.
It also offers many features that make it an efficient tool for building data-driven applications in . NET.


### Data Seeding

data seeding is a process of inserting an initial set of data into the database.

 It can be accomplished in several in EF Core:

- Model seed data: where the data is associated with an entity type in the model configuration

- Manual migration customization: where explicit calls to InsertData(), UpdateData(), and DeleteData() are added to the migration

- Custom initialization logic: where DbContext.SaveChanges() is used before the main application logic to seed the data

The choice of which way to use depends on the application requirements and constraints.


### User secrets

In .NET Core, User secrets provide a secure way to store sensitive user information separately, such as API keys and connection strings.

By enabling user secrets, we can store this confidential data in a secrets.json file, which is not uploaded to source control.

It can be easily managed through Visual Studio, and the stored secrets can be accessed in the application using the IConfiguration interface.

--------------------------------------------------

## Class 13 - Dependency Injection & Repository Design Pattern


1. **Dependency Injection:**
Dependency Injection (DI) is a design pattern in .NET, used to achieve loose coupling between components. 
It allows the dependencies of a class to be "injected" from the outside instead of creating them internally. 



2. **Repository Design Pattern:**
repository pattern has two purposes: 
- it is an abstraction of the data layer 
- it is a way of centralizing the handling of the domain objects.

It abstracts the data storage details, allowing the rest of the application to interact with data objects using a simplified interface. 


When combined with an ORM like Entity Framework, the pattern simplifies data access code, the Repository acts as an intermediary between domain objects and data mapping, providing a clear separation of dependencies and a organize working with data sources.

3. **SOLID Principles:**
SOLID is a set of five design principles for writing maintainable and scalable object-oriented software:

   - **Single Responsibility Principle (SRP):** A class should have only one reason to change, meaning it should have a single responsibility or purpose.
   - **Open/Closed Principle (OCP):** Software entities (classes, modules, etc.) should be open for extension but closed for modification, allowing new functionality to be added without altering existing code.
   - **Liskov Substitution Principle (LSP):** Objects of a superclass should be replaceable with objects of its subclasses without affecting the correctness of the program.
   - **Interface Segregation Principle (ISP):** Clients should not be forced to depend on interfaces they do not use, promoting the creation of specific interfaces for individual use cases.
   - **Dependency Inversion Principle (DIP):** High-level modules should not depend on low-level modules. 
Both should depend on abstractions, this principle encourages the use of dependency injection to achieve loose coupling.



5. **Why SOLID Matters:**

1- **Single Responsibility Principle (SRP):**
A class should have only one reason to change, meaning it should serve a singular purpose. Avoiding Swiss Army knife-like complexity in code brings clarity and maintainability by keeping methods focused and short.

2- **Open Closed Principle (OCP):**
Modules should be open for extension but closed for modification. Instead of constantly editing base code, use extensions like polymorphism to alter or add functionality, reducing the risk of introducing bugs.

3- **Liskov Substitution Principle (LSP):**
Subclasses should be substitutable for their base classes without impacting the client code's functionality. Just as ordering a salad at a restaurant doesn't change how you eat it, derived classes must seamlessly integrate with the client code.

4- **Interface Segregation Principle (ISP):**
Prefer having client-specific interfaces over a general-purpose one. Fine-grained interfaces prevent analysis paralysis and offer tailored options for consuming classes.

5- **Dependency Inversion Principle (DIP):**
Depend on abstractions, not concrete implementations. Code that directly instantiates concrete classes limits flexibility. Using interfaces enables easy switching between implementations, akin to driving different cars without altering your driving code.


--------------------------------------------------

## Class 14 - Navigation Properties and Routing

#### ASP.NET MVC Routing Overview (C#)


The tutorial introduced how ASP.NET Routing works, and how incoming requests are mapped to specific controller actions based on the URL structure and the route table.

It mentions the Global.asax file that contains event handlers for ASP.NET application lifecycle events.
In the Global.asax, the route table is created during the Application_Start event.
When an MVC application first starts, the Application_Start() method is called. This method, in turn, calls the RegisterRoutes() method. The RegisterRoutes() method creates the route table.


#### Routing in ASP.NET Core

**Routing is responsible for matching incoming HTTP requests and dispatching those requests to the app's executable endpoints.**
It plays a role in determining how the application responds to different URLs and HTTP methods.

The routing system can handle different types of HTTP requests like (GET, POST, PUT, DELETE) and map them to different endpoints.

In ASP.NET Core, the routing system is responsible for interpreting the request URL and extracting relevant information like controller, action, and parameters, in order to invoke the appropriate code to handle the request. 

The routing system works with a set of rules called routes, which defines is a pattern to match the incoming request URL and extracts relevant data from it.


--------------------------------------------------

## Class 15 - Trees

Trees

#### Basic concepts:

Node - A Tree node is an element that may contain its own value, and references to other nodes
Root - The root is the node at the beginning of the tree
K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
Left - A reference to one child node, in a binary tree
Right - A reference to the other child node, in a binary tree
Edge - The edge in a tree is the link between a parent and child node
Leaf - A leaf is a node that does not have any children
Height - The height of a tree is the number of edges from the root to the furthest leaf



## Traversals
There are two categories of traversals when it comes to trees:

1- Depth First
Depth first traversal is where we prioritize going through the depth (height) of the tree first.
It starts from the root node and explores as far as possible along each branch before backtracking to the previous node.
DFS uses a stack data structure (or recursion) to keep track of nodes to be visited next.

Here are three methods for depth first traversal:

Pre-order: root >> left >> right

In-order: left >> root >> right

Post-order: left >> right >> root


2- Breadth First
It starts from the root node and visits all the nodes at the same level before proceeding to the next level.

BFS uses a queue data structure to keep track of nodes to be visited next.


## Binary Tree Vs K-ary Trees

#### Binary trees:  allows each node to have only 2 childs
#### K-ary Trees: In this type of tree we use K to refer to the maximum number of children that each Node is able to have.

The Big O time complexity for inserting a new node is O(n)


## Binary Search Tree
 (BST) is a type of tree that does have some structure attached to it. In a BST, **nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.**

Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.

### The best way to approach a BST search is with a **while loop** We cycle through the while loop until we hit a leaf, or until we reach a match with what we’re searching for.

The Big O time complexity of insertion and search operations in a balanced Binary Search Tree (BST) is O(log n), where "n" is the number of nodes in the tree. However, in an unbalanced BST, the time complexity can degrade to O(n), making it behave like a linked list. To ensure efficient operations, maintaining balance using AVL trees or Red-Black trees is crucial.



--------------------------------------------------

## Class 16 - Data Transfer Objects


### Data Transfer Objects (DTOs)

####  A DTO is an object that defines how the data will be sent over the network.

Currently, the API exposes database entities directly to clients, but that approach may not always be ideal. By using DTOs, the shape of data sent to clients can be customized, offering benefits such as removing circular references, hiding specific properties, reducing payload size, and decoupling the service layer from the database layer.

By implementing DTOs, the API becomes more flexible in controlling the data sent to clients, allowing for better data abstraction and reducing unnecessary exposure to internal database structures. 



## How to use Data Transfer Objects in ASP.NET Core

A Data Transfer Object (DTO) is used as a container to encapsulate data and pass it from one layer of the application to another.

**(Usually, DTOs are used in the service layer to return data back to the presentation layer.)**

**The biggest advantage of using DTOs is decoupling clients from your internal data structures.**
By doing so, changes to either layer can be made independently, promoting flexibility and maintainability. 

DTOs also facilitate data hiding by allowing developers to return only the required data, enhancing security and privacy.
To ensure immutability and avoid unwanted modifications, DTOs are typically designed to be immutable. 

--------------------------------------------------

## Class 17 - Testing and Swagger and Deployment

## Swagger

Swagger (OpenAPI) is a specification for describing REST APIs. It allows both computers and humans to understand the capabilities of a REST API without direct access to the source code. 

Its main goals are to Minimize the amount of work needed to connect decoupled services and document them accurately.


#### Swagger UI: is a web-based interface that displays information about the service using the generated OpenAPI specification, allowing users to test and interact with API endpoints easily.


## Unit Testing

This tutorial focuses on writing unit tests for ASP.NET MVC controllers. It covers three key scenarios: 

1. Testing the View: how to test whether the controller's action method returns the correct view. It uses `ViewResult.ViewName` to verify that the expected view is returned.

2. Testing View Data: It explains how to test the data passed to the view using ViewData. The tutorial shows how to access the model passed to the view and validate its properties.

3. Testing Action Results: How to test different types of action results returned by a controller based on input parameters.



--------------------------------------------------

## Class 18 - Identity

### Intro to Identity


**ASP.NET Core Identity is an API that provides user interface login functionality;** and manages various user-related tasks such as user registration, password management, roles, and token-based authentication. 

It provides a way to create and handle user identities with claims, which represent specific facts about users.

Users can either create an account with login information stored in Identity or use external login providers like Google, Microsoft Account, etc.

Identity is commonly configured with a SQL Server database to store user data, but other persistent stores like Azure Table Storage can be used as well. 


The tutorial includes steps for Creating an ASP.NET Core Web Application project with Individual User Accounts:

1. Create new ASP.NET Core Web App project and name the project as desired.
2. In the Authentication type input, select Individual User Accounts.
3. Click OK to create the project with authentication enabled.
4. Visual Studio will set up the project with authentication using Identity framework and related components.
5. Build and run the project to see the basic authentication setup in action, which can be extended to fit our requirements .






### Identity Demystified

ASP.NET Core 2.0 Authentication and Authorization System Demystified

The system uses verbs like Authenticate, Challenge, SignIn, SignOut, and Forbid to execute authentication and authorization tasks.

Authentication handlers are responsible for implementing these behaviors, and they are registered with the authentication middleware. This middleware runs on every request, allowing the system to check user authentication and authorization and handle requests accordingly.

By using these components together, you can effectively authenticate and authorize users to access resources on your website.


--------------------------------------------------

## Class 19 - Roles, Claims and JWT Tokens


### Claims-Based authorization

When an identity is created it may be assigned one or more claims issued by a trusted party.
**A claim is a name-value pair that represents what the subject is, not what the subject can do.**

For example, the claim name would be DateOfBirth, and the claim value would be your date of birth.

An identity can contain multiple claims with multiple values and can contain multiple claims of the same type.

claims-based authorization in ASP.NET Core lets us control who can access a part of the application, based on specific attributes or characteristics (claims) associated with a user's identity. 

Main Steps:

1- we define an authorization policy:
```
builder.Services.AddAuthorization(options =>
{
   options.AddPolicy("EmployeeOnly", policy => policy.RequireClaim("EmployeeNumber"));
});
```
2- use authorization:
```
app.UseAuthorization();
```
3- Apply the policy using the Policy property on the [Authorize] attribute to specify the policy name:
```
[Authorize(Policy = "EmployeeOnly")]
```





### Intro to Claims

Authentication vs Authorisation:

Authentication is about identifying who you are, while authorization is about determining what you're allowed to do.

In ASP.NET Core, claims-based authorization is used to control access based on attributes associated with a user's identity.

Claims-based authorization is more flexible than role-based authorization. For example, a user might have a passport identity and a driver's license identity, each with different claims.

Identities in ASP.NET Core are ClaimsIdentity objects. Each identity contains claims (e.g., "FirstName," "DateOfBirth"), and multiple identities can belong to a single user, forming a ClaimsPrincipal.




### JWT Authentication

**JSON Web Token (JWT) is a way to represent claims to be transferred between two parties.**
The authentication server generates a JWT token when a user successfully logs in or authenticates.
The claims in a JWT are encoded as a JSON object.

The token contains encoded claims (information) about the user, such as their identity, roles, and permissions.

The token is digitally signed using a secret key known only to the authentication server.


Using JWT for authenticating server APIs:

1- Generate Token: After user authentication, the server generates a JWT token containing user info and signs it with a secret key.

2- Send Token: The server sends the JWT token back to the client (requesting server), which stores it securely.

3- Access API: When accessing a protected API, the client includes the JWT token in the request's Authorization header.

4- Verify Token: The resource server (API) validates the token's signature, decodes it, and checks user claims.

5- Grant Access: If the token is valid and user claims match, the API processes the request and provides data.

6- Token Expiry: Tokens may have expiration; clients can request new tokens when needed.


--------------------------------------------------

## Class 26 - Intro to MVC


### Azure Dev Ops

Azure DevOps is a set of development tools, that offers a range of features to help teams plan, develop, test, deliver, and monitor applications efficiently. 


### Learn Basics Of MVC Architecture

MVC is a design pattern that improves web application development efficiency compared to traditional ASP.NET Web Application approaches. In the traditional approach, user actions and views are tightly linked; while MVC separates the user interface (View) from the user actions (Controller).

MVC eliminates the use of View State, which reduces the heaviness of web pages, enhances efficiency, and reduces response time.

Also, Its loose coupling of UI and action logic makes testing more manageable.


#### MVC components: Model, View, and Controller, each responsible for different aspects of the application.

Models encapsulate application objects, Views define the UI using the Razor Engine, and Controllers handle user requests, returning responses by loading appropriate Views with data from Models. 

The Controller's methods, called actions, are crucial, and routing maps incoming requests to the appropriate actions. 

and we have the Data Access Layer (DAL) that is responsible for connecting with the database.

The article recommends ASP.NET MVC for lightweight and large-scale applications, especially when developed by a team, while suggesting traditional ASP.NET Web Application Framework for RAD models and smaller-scale projects.Tag Helpers in ASP.NET Core


### What are Tag Helpers
Tag Helpers enable server-side code to participate in creating and rendering HTML elements in Razor files.

There are many built-in Tag Helpers for common tasks - such as creating forms, links, loading assets, and more - and even more available in public GitHub repositories and as NuGet packages.

Tag Helpers also enhance productivity by offering rich IntelliSense support, promoting reusability and effective code generation.
They bring benefits like automatically managing cache busting for images through the ImageTagHelper, reducing manual effort and errors.

Tag Helper scope is managed using directives like @addTagHelper and @removeTagHelper. The @addTagHelper directive makes Tag Helpers available to views, and the @removeTagHelper directive removes previously added Tag Helpers. By leveraging these directives, developers can control the availability of Tag Helpers in specific views or directories.



#### Bootstrap

A popular open-source front-end framework that provides a collection of pre-designed, responsive HTML, CSS, and JavaScript components.

The tutorial was very beneficial .

--------------------------------------------------

## Class 27 - MVC Forms

### 4 Ways To Create Form In ASP.NET MVC :


Forms - Weakly Typed (Synchronous)

Forms - Strongly Typed (Synchronous)

Forms - Strongly Typed AJAX (Asynchronous)

Forms – HTML, AJAX and JQUERY

Step 1: Create a New ASP.NET MVC Project MvcForms. 
Step 2: Create a model class 


### 1. Forms - Weakly Typed (Synchronous):

```
@using (Html.BeginForm("SubmitForm", "Home", FormMethod.Post))
{
    <input type="text" name="username" placeholder="Username">
    <input type="password" name="password" placeholder="Password">
    <button type="submit">Submit</button>
}
```
Controller Action:

```
public ActionResult SubmitForm(string username, string password)
{
    // Process form data
    return View();
}
```


### 2. Forms - Strongly Typed (Synchronous):
Model:
```
public class LoginForm
{
    public string Username { get; set; }
    public string Password { get; set; }
}
```
View:

```
@model LoginForm

@using (Html.BeginForm("SubmitForm", "Home", FormMethod.Post))
{
    @Html.TextBoxFor(m => m.Username, new { placeholder = "Username" })
    @Html.PasswordFor(m => m.Password, new { placeholder = "Password" })
    <button type="submit">Submit</button>
}
```

Controller Action:
```
[HttpPost]
public ActionResult SubmitForm(LoginForm model)
{
    // Process form data using the model
    return View();
}
```

### 3. Forms - Strongly Typed AJAX (Asynchronous):
Example:

View:

```
@model LoginForm

@using (Html.BeginForm("SubmitForm", "Home", FormMethod.Post, new { @id = "loginForm" }))
{
    @Html.TextBoxFor(m => m.Username, new { placeholder = "Username" })
    @Html.PasswordFor(m => m.Password, new { placeholder = "Password" })
    <button type="submit">Submit</button>
}

<script>
    $(function () {
        $('#loginForm').submit(function (e) {
            e.preventDefault();
            $.ajax({
                url: '@Url.Action("SubmitForm", "Home")',
                type: 'POST',
                data: $(this).serialize(),
                success: function (data) {
                    // Handle success response
                },
                error: function () {
                    // Handle error
                }
            });
        });
    });
</script>

```
Controller Action:

```
[HttpPost]
public ActionResult SubmitForm(LoginForm model)
{
    // Process form data using the model
    return Json(new { success = true });
}
```




### 4. Forms – HTML, AJAX, and jQuery:

View:

```
<form id="loginForm">
    <input type="text" id="username" placeholder="Username">
    <input type="password" id="password" placeholder="Password">
    <button type="button" id="submitButton">Submit</button>
</form>

<script>
    $(function () {
        $('#submitButton').click(function () {
            var username = $('#username').val();
            var password = $('#password').val();
            $.ajax({
                url: '@Url.Action("SubmitForm", "Home")',
                type: 'POST',
                data: { username: username, password: password },
                success: function (data) {
                    // Handle success response
                },
                error: function () {
                    // Handle error
                }
            });
        });
    });
</script>
```



Controller Action:

```
[HttpPost]
public ActionResult SubmitForm(string username, string password)
{
    // Process form data
    return Json(new { success = true });
}

```



--------------------------------------------------

## Class 28 - Authorization, Cookies

### HTTP Cookies


**HTTP cookie (web cookie, browser cookie) is a small piece of data that a server sends to a user's web browser.**
The browser may store the cookie and send it back to the same server with later requests.

HTTP cookie is usually used to tell if two requests come from the same browser—keeping a user logged in, for example. It remembers stateful information for the stateless HTTP protocol.



#### Cookies are used for three purposes:

1- Session management
Logins, shopping carts, game scores, or anything else the server should remember

2- Personalization
User preferences, themes, and other settings

3- Tracking
Recording and analyzing user behavior

## Setting and reading cookies

with ASP.NET MVC, you can send a cookie to the client, in easy way:

To set a cookie, you use the HttpContext.Response.Cookies.Append method, specifying a name and a value for the cookie.
```
HttpContext.Response.Cookies.Append("user_id", "1");
```

HttpContext class allow us to access the Cookies property, so we used the Response property.

To read a cookie, you use the HttpContext.Request.Cookies property.
```
var userId = HttpContext.Request.Cookies["user_id"];
```

----

The article provides an example where a cookie is used to determine whether a user has visited a page before. 

If the cookie is not present, it is added with the current date and time.
If the cookie is present, the first visit date is displayed to the user.

---
**"CookieOptions"** : A class that allows you to customize cookie settings such as expiration, domain, and path. 

---

### HTTP cookies explained

Cookies are commonly used to manage user sessions and store user-specific information.

Cookies are created by web servers using the `Set-Cookie` HTTP header. 
This header includes information such as the cookie's name, value, expiration date, domain, path, and security settings.

Cookies can be session-based (deleted when the browser is closed) or persistent (with an expiration date).



--------------------------------------------------

## Class 29 - Azure Blob Storage




### Introduction to Azure Blob Storage

#### Azure Blob Storage is Microsoft's cloud-based object storage solution.
Blob Storage is optimized for storing huge amounts of **unstructured data**, such as text or binary data.

**Blob Storage is designed for:**

1. Serving images or documents directly to a browser.
2. Storing files for distributed access.
3. Streaming video and audio.
4. Writing log files.
5. Data backup, restore, disaster recovery, and archiving.
6. Data analysis by on-premises or Azure-hosted services.

**Access Methods:**
Users or client applications can access Blob Storage objects via HTTP/HTTPS, Azure Storage REST API, Azure PowerShell, Azure CLI, or Azure Storage client libraries. These libraries are available for multiple programming languages.



**Blob Storage Resources:**
Blob Storage offers three primary resources:

1. **Storage Account:** Provides a unique namespace for data storage. It combines your account name with the Blob Storage endpoint.

2. **Container:** Organizes blobs, similar to directories in a file system. Containers have unique names and can store multiple blobs.
- Container names must be lowercase.


3. **Blob:** Azure Storage supports three types of blobs: Block blobs, Append blobs, and Page blobs. They serve various purposes, including storing text, binary data, and virtual hard drive files.



**Moving Data to Blob Storage:**
Data can be migrated to Blob Storage using tools like AzCopy, Azure Storage Data Movement library, Azure Data Factory, Blobfuse, Azure Data Box service, and Azure Import/Export service.



## Quickstart: Azure Blob Storage client library for .NET

Requirements:

1- Azure account

2- Azure Storage Account

3- .NET SDK: install .NET SDK for your operating system.


**Setting Up:**

- Create a .NET console application.

- Install Azure Blob Storage Client Library:
 Install the Azure.Storage.Blobs package via NuGet.

- Set Up App Code: Replace the code in your Program.cs file with the provided code, including the necessary using statements.
```
using Azure.Storage.Blobs;
using Azure.Storage.Blobs.Models;
using System;
using System.IO;
```

- Authenticate to Azure:
You can use either passwordless or connection string-based authentication.

- Passwordless (Recommended):

Use DefaultAzureCredential from Azure Identity to manage authentication.
Assign roles to your Azure AD user account if you're developing locally.

- Connection String:
Authenticate using the account access key.
Be cautious when using this approach as it exposes the access key.

- Object Model:

Azure Blob Storage has a hierarchy: Storage Account > Container > Blob.

BlobServiceClient: Manipulates storage resources and blob containers.

BlobContainerClient: Manipulates storage containers and their blobs.

BlobClient: Manipulates storage blobs.





--------------------------------------------------

## Class 30 - Hash Tables


### Intro to Hash Tables
Terminology:

Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket.
An index could potentially contain multiple key/value pairs if a collision occurs.

Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

#### Hashtables are a data structure that utilizes key-value pairs, so every Bucket has a key and a value.

hashtables provide the ability to store the key into this data structure, and quickly retrieve the value, so we can do a lookup in an O(1) time complexity. This is done through what we call a hash.

A hash is the result of some algorithm taking an input string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

#### Hashtable uses a hash code to convert a key into an integer and then maps this integer to an index in an array. 

This algorithm may involve operations like adding or multiplying ASCII values and using modulo to find the index.


Insertion: 
1. Accept a key.
2. Calculate the hash code for the key.
3. Use modulo to determine the array index.
4. Store the key and value in the bucket at that index, potentially adding them to a linked list if needed.

Retrieval:
1. Accept a key.
2. Calculate the hash code for the key.
3. Use modulo to find the array index.
4. Access the bucket at that index.
5. Search through the bucket's linked list to find the key/value pair that matches the given key.

### Methods
set()

When adding a new key/value pair to a hashtable:

1. send the key to the hash() method.
2. Once you determine the index of where it should be placed, go to that index
3. Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
4. If something does exist, add the new key/value pair to the data structure within that bucket.


get()


The get() method takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

has()


The has() method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the hash() method and check the hashtable if the key exists in the table given the index returned.

keys()

The keys() method returns a collection (array) of unique hash keys.

hash()

The hash() method will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.


## Basics of Hash Tables

Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects. 

An example of using hashing in our lives is In universities, each student is assigned a unique roll number.

Hashing is implemented in two steps:

1- Hash Function: An element, often referred to as a key, is transformed into an integer using a hash function. This integer serves as an index for storing the original element in a hash table.

2- Storage in Hash Table: The element is then stored in a hash table at the computed index, making it easy to retrieve using the hashed key.

Here's how it works:
```
hash = hashfunc(key)
index = hash % array_size
```

In this process, the hash value is calculated independently of the hash table's size, and it's then reduced to an index by using the modulo operator (%), ensuring the index falls within the valid range of 0 to array_size - 1.



--------------------------------------------------

## Class 31 - Razor Pages

### Introduction to Razor Pages in ASP.NET Core

Razor Pages simplify the development of web applications by combining the UI and the server-side code in a single Razor Page file.

1. Razor Pages is enabled in Program.cs:

   builder.Services.AddRazorPages();
app.MapRazorPages();


2. Basic Razor Page:
A basic Razor Page is shown with a .cshtml file. It includes HTML content and server-side code.
@page Directive: makes the file into an MVC action, which means that it handles requests directly, without going through a controller.

3. PageModel: Razor Pages often include a corresponding PageModel class (C#) that defines the server-side behavior for the page. The PageModel class contains methods and properties that interact with the page's content and data.

### Razor Pages vs. MVC

Both of these frameworks  ASP.NET MVC (Model-View-Controller) and Razor Pages in ASP.NET Core are used to build server-side web applications.
Both have advantages and we should depend on the requirements to choose which one to use:

**ASP.NET MVC:**

1. **Request Handling:** MVC routes requests to controller actions using the routing engine. The URL structure typically follows the pattern "/<controller name>/<action name>."

2. **Controller Logic:** Application logic, including request validation, business logic, and service calls, resides in controller actions.

3. **View Handling:** MVC actions often return views, and the framework looks for views in a default "Views" folder based on naming conventions.

4. **Data Display:** Data to be displayed in views is typically passed through view models.

5. **Folder Structure:** MVC applications have a standard folder structure with separate folders for controllers, views, and view models.

**Razor Pages:**

1. **Request Handling:** Razor Pages directly route requests to Razor Page files in the "Pages" folder based on request names (e.g., "/contact" routes to "Contact.cshtml").

2. **Page Model:** Each Razor Page can have a corresponding Page Model class. Logic for HTTP verbs (e.g., GET, POST) resides in these Page Models.

3. **View Handling:** Since requests are routed directly to Razor Pages, there's no need to locate separate views. The view is the Razor Page itself.

4. **Data Display:** Data for display in Razor Pages is often set as properties in the Page Model class.

5. **Folder Structure:** Razor Pages applications primarily use the "Pages" folder, and subfolders are respected in routing.


--------------------------------------------------

## Class 32 - View Components


### Intro to View Components

**View Components in ASP.NET Core are a type of reusable component that encapsulates a piece of view logic.** They are similar to partial views but offer more flexibility and reusability. 

Benefits of using View Components:

- Code reuse: View Components allow you to reuse code that is common to multiple views. This can make your code more maintainable and easier to update.

- Partial view rendering: View Components can be used to render partial views from within other views. This can be useful for breaking up your views into smaller, more manageable pieces.

- Performance: View Components can improve the performance of your application by rendering only the part of the view that is needed. This is because View Components are typically smaller and less complex than controllers.

- Maintainability: View Components can make your code more maintainable by encapsulating common functionality into reusable components. This makes it easier to understand and modify your code.

Steps:

1- create a class that inherits from ViewComponent
```

public class GreetingViewComponent : ViewComponent
{
    public IViewComponentResult Invoke(string name)
    {
        return View(name);
    }
}
```

2- To call this View Component from a view, you would use the following code:

HTML
```

@await Component.InvokeAsync<GreetingViewComponent>("Bard")
```

3- This would render the following HTML:
HTML
```
<p>Hello, Bard!</p>
```
--------------------------------------------------

## Class 33 - Sendgrid

 
### Sending Email with Microsoft Azure

To get started with Twilio SendGrid and Azure:

1) Create an Azure Subscription from Azure Portal 

2)  you will see a list of your current Azure subscriptions, You can add a new Twilio SendGrid service.

3) Create a Twilio SendGrid account:
From the Azure portal home page, select Marketplace under Azure services. you can search for it by selecting More Services.
 
   The Azure Marketplace provides many services, including the Twilio SendGrid email service. You can find it by searching for "Twilio SendGrid." You will also find it under Software as a Service (SaaS).



4) Click the Twilio SendGrid resource -> Select Set up + subscribe.
You will be taken to a page where you can assign your Twilio SendGrid account to an Azure Subscription and Resource Group -> when you finish, select Review + subscribe.

5) click the Configure Account Now button to be taken to the Twilio SendGrid App. You will also receive an email when the subscription setup is complete.



6) Twilio SendGrid account setup: 
Before sending your first email, you will need to complete the following Twilio SendGrid account setup. (These requirements help secure your account and keep your messages from landing in spam folders).

- Configure Two-factor authentication
- Create an API key
- Complete Sender Authentication

7) Navigate to Two-Factor Authentication in the Twilio SendGrid Settings menu, and click Add Two-Factor Authentication. You will need to enter a phone number to complete the 2FA process

8) API keys
API Keys authenticate your application, mail client, or website with Twilio SendGrid services. Unlike a username and password, API keys are scoped to provide access only to the services you select. You can also delete and create API keys without impacting your other account credentials. For these reasons, Twilio SendGrid requires you to connect to its services using API keys.

9) Create an API key
In the Twilio SendGrid App, navigate to API Keys in the Settings menu, and select Create API Key.
A modal will open where you can create your key. You must name the API key — we recommend something that will clearly differentiate the key from others you may create in the future.
You must also select the type of key you want to create. Twilio SendGrid provides three types of API key:

    Full Access

    Restricted Access

    Billing Access

    You can limit a key's capabilities by creating a Restricted Access key and selecting a subset of all the possible permissions

    Use an API key

    Twilio SendGrid's v3 APIs expect an API key to be passed in an Authorization header as a Bearer Token.


   When using Twilio SendGrid’s SMTP integration, you will set your API key as a password via Basic Authentication. Your username must always be the string, “apikey.” Using the account credentials (username and password) you set up through Azure will fail, so be sure to set your password to the 14 digit API key provided by the Twilio SendGrid App. Your account credentials are separate from the credentials used to authenticate with Twilio SendGrid’s APIs and SMTP services.
```
   username: "apikey"
   password: <your-api-key>
```


10) Sender Authentication

    Twilio SendGrid requires customers to complete Sender Authentication. This requirement protects your domain's reputation as an email sender and helps uphold legitimate sending behavior by Twilio SendGrid customers.

    Setup includes domain authentication. Twilio SendGrid will provide DNS records that you must add to your domain.



--------------------------------------------------

## Class 34 - Payment Processing

### How Credit Card Processing Works:

1- Authorization Procedure: When a customer initiates a credit card payment, the payment details are transmitted from the merchant's system to a payment gateway.
The gateway then forwards this information to the bank responsible for issuing the credit card, and the request must be approved.

2- Capture and Settlement:  transfer of funds from the customer's account to the merchant's account.

3- Clearing: The payment details are relayed to the appropriate card network (e.g., Visa, MasterCard) for clearing purposes. This network plays a pivotal role in reconciling transactions between various banks involved.

4- Funding: Subsequently, the acquiring bank, which represents the merchant, receives the funds from the issuing bank. This marks the culmination of the settlement process, with the merchant gaining access to the funds.

5- Chargebacks: customers may dispute specific charges, leading to what is known as chargebacks. 

### Concepts

1. **Merchant Accounts**: The process begins with having a bank checking account, which is then linked to a Merchant Account. A Merchant Account connects to the credit card processing network and ensures that credit card transactions are processed correctly and securely. It can be visualized as the modern equivalent of a card-swipe machine.

2. **Internet Merchant Account**: This is a specialized Merchant Account designed to accept online credit card transactions. It may work alongside a regular Merchant Account and is crucial for online payment processing.

3. **Payment Gateway**: The Payment Gateway is responsible for securely transmitting credit card information to the Internet Merchant Account. It serves as a router and handles tasks like fraud checking and maintaining reliable links with merchants. Major Payment Gateways mentioned include Authorize.net, PayPal, and First Data.

4. **Your Application**: Applications can interact with the Payment Gateway in different ways. Simple applications might redirect users to a web page on the Gateway for credit card processing, while more sophisticated applications can control the entry of credit card information through an API. Security requirements, especially for third-party applications, mandate that credit card information should not be stored on the application server.

5. **Validation, Refunds, and Settlement**: When a user enters credit card information, it is sent securely to the Payment Gateway. If the card is cleared, the Gateway returns order numbers for future reference. This avoids storing credit card information. Refunds are typically made using these reference order numbers. Settlement, managed by the Merchant Account, involves transferring funds from the buyer to the merchant's bank, which takes several business days.

6. **Fees**: There are various fees associated with online credit card processing. Merchant Accounts may have setup fees, recurring monthly fees, and per transaction fees. 


--------------------------------------------------

## Class 35 - Graphs

### Graphs
Graph is a non-linear data structure, used to to represent and analyze relationships or connections between various objects.
It consists of:
- vertices (nodes) 
-  edges:  connections or links between vertices in the graph

## Types of graphs:

Undirected Graph: In this type, edges have no direction, meaning they connect vertices without specifying a specific order.

Directed Graph (Digraph): In a directed graph, each edge has a direction, indicating a one-way relationship from one vertex to another.

Complete Graph: In a complete graph, every vertex is directly connected to every other vertex.

Connected Graph: A connected graph is one where there is a path between every pair of vertices.

Disconnected Graph: This type contains multiple components, and not every vertex is reachable from every other vertex.

Acyclic Graph: An acyclic graph has no cycles, meaning there are no closed loops of vertices and edges.

Cyclic Graph: A cyclic graph contains cycles, which are closed loops of vertices and edges.


--------------------------------------------------

## Class 37 - JAM Stack

### What is the JAMstack?

JAMstack is a software architecture and philosophy that adheres to the following components: Javascript, APIs, and Markup.



What makes up the JAMstack?
it's typically comprised of 3 components:
J: Javascript
A: APIs
M: Markup

#### Key advantages of JAMstack:

- Pre-rendering: JAMstack sites generate HTML during the build process, allowing for fast and efficient content delivery to end-users. 

- API-driven: JAMstack applications rely on APIs to access dynamic data and services. This approach allows for a clean separation of concerns, with the front end and back end being decoupled.

- Version Control: JAMstack projects are typically managed using version control systems like Git. 

- Scalability: With static files and cached content, JAMstack sites are highly scalable and can handle traffic spikes effectively. 

- Security: Since JAMstack sites have a reduced attack surface (no server-side logic to exploit), they are inherently more secure. Access to APIs can be controlled with proper authentication and authorization.

- Simplicity:  by breaking down complex applications into smaller parts. 

