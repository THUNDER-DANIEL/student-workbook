# Day 3 - FORMS AND TEMPLATES
Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions



What are the two common operations that we will set in the handler?

        Get and Set
What do you have to make sure you are doing with every Get to insure the value does not become undefined?

        Watch out for it's dault implementation is to return the value stored in that key in the object. It must be overrode- the handler object is basically an object with a set of traps that would trigger whenever an object property is being accessed.

What are some of the benefits of the proxy object that we are using in our structure for applications?

        
        The Proxy object enables you to create a proxy for another object, which can intercept and redefine fundamental operations for that object.
        Proxy is created with two parameters:
        -target: the original object which you want to proxy
        -handler: an object that defines which operations will be intercepted and how to redefine intercepted operations.

https://github.com/THUNDER-DANIEL/greglist