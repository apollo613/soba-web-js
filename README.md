
# SoBA Web Curriculum

### Lesson 4: Introduction to JavaScript


#### Overview

For this lesson you will be creating a number of web pages with embedded JavaScript. The purpose of the lesson is to introduce you to the JavaScript standard library, basic DOM manipulation and to JavaScript object literals and function callbacks.

#### Instructions

Again, make sure you fork this repository to your own account and clone it like you did for the first two assignment.

Keep up the habit of branching in git, making your changes, and then merging back into your main branch. As in Assignment 3, instead of branching from main, create a "development" branch first immediately after you clone the repository, and branch from this line when you edit the individual files.

#### Editing the files

You will be creating a number of html files from scratch. Your HTML will be minimal and will primarily support any DOM manipulations you need to make. Blank starting files have been provided. You will be editing the following:

1. input.html
2. person.html
3. callback.html
4. map.html
5. higher-order.html
6. self-executing.html

Remember to use python's SimpleHTTPServer for viewing your pages!

In order for your scripts to execute correctly, make sure you place your JavaScript at the bottom of the page. The script tag should be the last tag before the html closes.

Use Chrom's developer console to try out your JavaScript in a REPL and to interact with the functions you define.

#### Input.html

The point of this exercise is to introduce you to some of JavaScript’s standard library functions and basic dom manipulation. Refer to the documentation for assistance.

Create a JavaScript program that prompts a user to enter a comma separated list of grocery items. Convert their input, which will be a string, into an array of grocery items. Sort the array so that the items appear in alphabetical order. Now write the items into the web page, one paragraph for each item. Do not use a for loop. Instead use the forEach method we discussed in class.


The purpose of this assignment is introduce object literals and functions attached to object literals.




The purpose of this assignment is to introduce you to inline object literals and a design pattern that uses callback functions.

The purpose of this assignment is expose you to anonymous functions and functional programming styles.

Using our map function, convert an array of strings containing numeric values to an array of plain numbers. For example, your function would convert the array [ “1”, “2”, “3”, “4”, “5” ] to the array [ 1, 2, 3, 4, 5 ]. Do not use a for loop, and use an inline anonymous function to do the conversion.

#### Higher-order.html

The purpose of this exercise is to expose you to higher order functions and to mess with your heads a bit.

Write a function called *root* that takes a single parameter *n*. This function **returns a function** that takes a single parameter *x* and calculates the nth root of x.















