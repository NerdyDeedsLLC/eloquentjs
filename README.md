# Eloquent JavaScript

This repository presents solutions to the excercises in the third edition of Marijn Haverbeke's *Eloquent JavaScript* ([ISBN 978-1-59327-950-9](https://read.amazon.com/kp/embed?asin=B07C96Q217&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_fxZ.EbDN7B1DB)).

## Running Solutions

These solutions were written to be run within the [Node.js](nodejs.org) runtime environment. After installing Node.js and downloading this repository, to run an excercise simply run node with the excercise name as a parameter from the Terminal.  For example:

````bash
$ node chapter01/helloworld.js 
````

## Notes

The excercise solutions attempt to only use the concepts that have been introduced up to that
point in the book.  For example, chapter one solutions to not use functions since functions
are introduced in chapter two.

## Solutions

### Chapter One - Values, Types, and Operators

* helloworld.js - A bonus since chapter one does not have any exercises. But, we might as well say, "Hello!"

### Chapter Two - Program Structure

* triangle.js - Outputs a triangle to the console
* fizzbuzz.js - Outputs the classic [Fizz buzz game](https://en.wikipedia.org/wiki/Fizz_buzz) and [FizzBuzz programming interview question](https://blog.codinghorror.com/why-cant-programmers-program/) for numbers from 1 to 100
* chessboard.js - Outputs an NxN [chessboard](https://en.wikipedia.org/wiki/Chessboard) pattern to the console

### Chapter Three - Functions

* minimum.js - Implement min(), a basic Math.min function
* recursion.js - Demonstrates recursion by using a recursive isEven() function to determine if a number is even
* beancount.js - Implements a function, countLetters(), to count letters in a string and a second function, countBs(), to count the number of uppercase letter 'B's in a string

### Chapter Four - Data Structures: Objects and Arrays

* deepcompare.js - Implements a deep comparision of equality between two objects
* list.js - Implements functions to manipulate a list data structure (single linked)
* range.js - Implements functions to create a range of numbers and sum and array
* reverse.js - Reverses the elements of an array using two approaches

### Chapter Five -- Higher-Order Functions

* flatten.js - Flattens arrays into a single array
* loop.js - A custom loop that tests and updates while processing
* every.js - Tests to see if all elements in an array pass a test
* dominant.js - Determines the dominant writting direction in a string of text

### Chapter Six -- The Secret Life of Objects

* vector.js - Defines a vector class
* groups.js - Defines a 'groups' data structure that is similar to the standard JavaScript set data structure
* iterable.js - Extends 'groups' so that it is iterable
* borrow.js - Illustrates how to borrow a method from another object