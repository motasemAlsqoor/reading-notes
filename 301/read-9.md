## functional programming 

Functional programming (FP) is the process of building software by composing pure functions. Nowadays, employers are looking for programmers who can draw on multiple paradigms to solve problems. Functional programming especially is gaining in popularity due to its efficiency and scalability to solve modern problems.(1)

Functional programming is a declarative programming paradigm where programs are created by applying sequential functions rather than statements.(1)

Each function takes in an input value and returns a consistent output value without altering or being affected by the program state.(1)

Functional programs execute many pure, single-purpose functions in sequence to solve complex mathematical or non-physical problems.

## Advantages of Functional programming

Easy debugging :Pure functions and immutable data make it easy to find where variable values are set.

Lazy evaluation: Functional programs only evaluate computations at the moment they’re needed. This allows the program to reuse results from previous computations and save runtime.

Modular: Pure functions do not rely on external variables or states to function, meaning they’re easily reused across the program. Also, functions will only complete a single operation or computation to ensure you can reuse that function without accidentally importing extra code.

Enhanced readability: Functional programs are easy to read because the behavior of each function is immutable and isolated from the program’s state. As a result, you can predict what each function will do often just by the name!

Parallel programming: It’s easier to create parallel programs with a functional programming approach because immutable variables reduce the amount of change within the program. Each function only has to deal with user input and can trust that the program state will remain mostly the same!

## Concepts of Functional Programming

  Pure functions :

Pure functions have two properties:

1. they create no side effects
2. they always produce the same output if given the same input

### Immutability and states

Immutable data or states cannot be changed once set and allow a stable environment for a function’s output to be constant

## Recursion 

One major difference between object-oriented programming and functional programming is that functional programs avoid constructions like If-Else statements or loops that can create different outputs on each execution.

Functional programs use recursion in place of loops for all iteration tasks.

## First-class functions

Functions in functional programming are treated as a data type and can be used like any other value. For example, we populate an array with functions, pass them as parameters, or store them in variables.

## Higher Order functions

Higher-order functions can accept other functions as parameters or return functions as output. Higher-order functions allow us greater flexibility in how we make function calls and abstract over actions

## Functional composition

Functions can be sequentially executed to complete complex operations. The result of each function is passed to the next function as an argument. This allows you to call a series of functions with just a single function call.



## References

1. https://www.educative.io/blog/what-is-functional-programming-python-js-java

 
