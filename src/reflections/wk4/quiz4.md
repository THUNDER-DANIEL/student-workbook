# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
        synchronous code is running in sequence each statement waits for the previous statement to finish before continuing. Asynchronous code doesn't have to wait – your program can continue to run. 
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
        open–closed principle
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
                A callback function is a function that is passed as an argument to another function, to be “called back” at a later time. A function that accepts other functions as arguments is called a higher-order function, which contains the logic for when the callback function gets executed.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
        a Promise s a proxy for a value not 
        necessarily known when the promise is 
        created. Catching error with 
        try /catch

        1- pending: initial state, neither
         fulfilled nor rejected.

        2- fulfilled: meaning that the 
        operation was completed successfully.

        3- rejected: meaning that the 
        operation failed.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
                POST Method
                GET Method
                HEAD MEthod
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
        Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
 The Controller(s)
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
        Encapsulation is used to hide the values or state of a structured data object inside a class. It refers to the bundling of data with the methods that operate on that data
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
        200 - 299
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
        Server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request.
```