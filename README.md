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

## Class 4 - Readings: Linked Lists

##  Big O
Big O notation is a way to measure the efficiency of algorithms and data structures.
by big O we can analyze the performance based on the time complexity, space complexity, and the input size(n), for the best and the worst case scenarios

In this way, we can decide which is the best data structure or algorithm to use for the software.

## Linked lists
Linked lists are a data structure that has two types (singly and doubly).
linked lists have no fixed size and no index, and they don't require contiguous memory allocation, so it differs from arrays and it has their benefits of use.

Linked lists consist of nodes and pointers, where pointers are references to the next node in the SLL, and in DLL there are pointers for the next and previous nodes

we prefer to use Linked lists when we need flexibility for memory and we don't want a fixed size, but we don't prefer it when we need quick access for elements as it has linear complexity.