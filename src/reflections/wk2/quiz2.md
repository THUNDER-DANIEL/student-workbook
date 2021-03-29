# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
  ```   
        var / let / conts

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
    Set of statements that performs a task or calculates a value


**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
``` 
S — Single responsibility principle
O — Open closed principle
L — Liskov substitution principle
I — Interface segregation principle
D — Dependency Inversion principle

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
    fruit[2]
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
    Arrays have 2 ways of counting content within it's container. Length and zero based index. The most commonly used is the zero based index -meaning the very first item in array is going to be zer0 !
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them{})
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
    if(cookie){milk}else{moreCookies}

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
    i++ or i-- is the in/de-crement expression

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

        Document Object Model
        a .js file 

```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
       1. Undefined
       2. Boolean
       3. Number
       4. String
       5. BigInt
       6. Symbol
       7. Object
       8. Function
       9. null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
        Difference between parameters and arguments: Function parameters are the names listed in the function's definition. Function arguments are the real values passed to the function. Parameters are initialized to the values of the arguments supplied.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
        Primitive values are data that are stored on the stack. Reference values are objects that are stored in the heap. In addition to all of these, you're also give a little bit of extra space by the Operating System. This is called the heap. Any extra memory you need is allocated from this space. Memory allocated in this way is called dynamic memory.
```