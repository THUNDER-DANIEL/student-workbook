# Day 2 - JAVASCRIPT FUNCTIONS, OBJECTS, AND LOOPS


What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

    A Function Declaration defines a named function.
    Function definition is hoisted, thus allowing the function to be used before it is defined.
    A Function Expressions defines a named or anonymous function.Function Expressions are not hoisted, and therefore cannot be used before they are defined.
    An Arrow Function Expression is a shorter syntax for writing function expressions. Arrow functions do not create their own this value.

What is the difference between Parameters and Arguments?

     Difference between parameters and arguments: Function parameters are the names listed in the function's definition. Function arguments are the real values passed to the function. Parameters are initialized to the values of the arguments supplied.

What are higher order functions? Can you provide an example?

    When a function accepts another function as a parameter, or returns a function, it is called a higher-order function.

    function outside(inside()){

    }