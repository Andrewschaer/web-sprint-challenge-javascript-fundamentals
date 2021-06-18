# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

_You have **three hours** to complete this challenge. Plan your time accordingly._


## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead as the evaluate your solution.

## Interview Questions
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Briefly compare and contrast `.forEach` & `.map` (2-3 sentences max)

    #Both `.forEach` and `.map` are array methods that serve as higher-level functions that use callback functions to access the items in the specified array.  These array methods, however, differ in their purpose and output. The `.forEach` array method loops over each item in an array to perform a specified action, but does not natively return a new array, while the `.map` array method allows you to use a function to easily manipulate the data in the specified array and in doing so, returns a brand new array with that manipulated data.

2. Explain the difference between a callback and a higher order function.

    #A higher order function is one that can receive other functions as a argument for that function.  A callback function, however, is one that you can pass into a separate function as a argument.

3. Can you explain what a closure is and how you used it in the counter function? 

    #A closure occurs when a nested function is invoked and reaches out of its own functional scope to a higher-level scope (for example a parent function or of the global scope) to read in and utilize a variable declared there.  I used a closure in writing the counter function within the for loop function.  When defining the parameters of i, the for loop I wrote specified that the loop should continue to run as long as i was less than the variable 'number'.  The variable 'number' was declared in a higher-level scope than the for loop function, so when the for loop reaches out of its own scope to read in that variable ('number'), a closure occurs. 

4. Describe the four principles of the 'this' keyword.

    1. Window Binding:

      #Window binding occurs when using the "this" keyword when there is no additionally given context for what the "this" is referring to, therefore binding "this" at the highest scope level (global scope) to the window, which is an object containing all JS built-in functions, arrays and variable key-value pairs)
    
    2. Implicit Binding:

      #Implicit binding occurs when using the "this" keyword in a function that is within an object.  Here we are implying that the "this" is referring to the object and we can therefore use object methods using the "dot" notation. The "this" must be used after the object being referred to is already referenced.

    3. Explicit Binding

      #Explicit binding occurs when using the ".call", ".apply" or ".bind" methods on existing functions that contain "this", in order to override what the "this" keyword points to.

    4. New Binding

      #New binding occurs when using constructor functions, where the "this" keyword is referencing the new object that is created by the constructor function.

5. Why do we need super() in an extended class?

    #We need to use `super()` when creating an extended class in order to pass attributes up to the parent object constructor function so that the any objects created with the extended class constructor are created with the same object keys.  Extended classes can have their own unique object keys, but `super()` ensures that they will also have the same keys as their parent class.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2: Project Requirements

Your finished project must include all of the following requirements

#### Task A: Closure

This challenge takes a look at closures as well as scope. 
* [X] Find this challenge in the index.js file. Read the instructions carefully!

#### Task B: Objects and Arrays

Test your knowledge of advanced array methods and callbacks.
* [X] Find this challenge in the index.js file. Read the instructions carefully!

#### Task C: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [X] Find this challenge in the index.js file. Read the instructions carefully!

#### Task D: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [X] Find this challenge in the index.js file. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Goals 

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements! Please remember to comment out your stretch goals before you submit 

## Submission format

See Canvas for submission instructions 

