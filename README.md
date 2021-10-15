# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

.map converts data, returns a new array, and requires a return statement where the return is pushed into the new array. An example would be transforming an array of numbers by multiplying them all by a certain number.
.reduce walks through the array element-by-element, at each step adding the current array value to the result from the previous step. An example would be finding the total of prices in an array of object with prices.
.filter loops through an array and creates an array with a subset of elements from the original array. An example would be finding the cities with populations over 2 million in an array of cities w/population.

2. Explain the difference between a callback and a higher order function.

A callback is a function passed into another function as an argument to be executed later.
A higher order operates on other functions, either by taking them as arguments or by returning them.

A callback is not necessarily itself a higher order function, but a function which receives a callback as an argument is.

3. Explain what a closure is.

Closure gives the ability to put functions together. Code that exists elsewhere that we can use when we need them. We can pass variables down but can't pass back. Closure happens when inner function reaches into an outer scope to grab a value or variable. 

4. Describe the four principles of the 'this' keyword.

Global Binding - When the 'this' keyword is not resolved with any of the bindings, implicit, explicit or new, 'this' is bound to the window(global) object. In JS's strict mode, this will be undefined.
Implicit Binding - 80% of cases. Occurs when dot notation is used to invoke a function, to the left of the .operator.
New Binding - Used to create an object from the constructor function. The newly created 'this' binds to the object being created using the new keyword.
Explicit Binding - When a function with an object is outside of the execution context of the object. Occurs when .call(), .apply(), or .bind() are used on a function.

5. Why do we need super() in an extended class? 

When extending a class, the super() calls the parent class constructor to access the parent’s methods and properties. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
