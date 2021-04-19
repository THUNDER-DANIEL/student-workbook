# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
        Create, Read, Update, and Delete (CRUD)
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
                Create >POST
                Read   >GET
                Update >PUT
                Delete >DELETE
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
                Object–relational mapping
                Mongoose
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
                GET and POST
```
**5.** In a/an ____(1) ___ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an ______(2) _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
                1-Synchronous
                2-Asynchronicity
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ____1__ from "___2____"
let Schema = _____3___.Schema;
```
<!-- enter you answer in the space below -->
```
                1-mongoose
                2-"mongoose"
                3-mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is basically a 
function that will the receive the Request and Response objects, just like your route Handlers do. 
```
**8.** The ______  1 pipeline delivers information from the client while the ______2  pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
        1-Request
        2-Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
        async findAll(query){
                let res = await dbContext.find({winter})
                }
```