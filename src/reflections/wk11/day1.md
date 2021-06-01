# Day 1 - INHERITANCE AND INTERFACES

Read Foundations of C# > C# Inheritance and answer the following questions

What does Inheritance accomplish for us in C#?

        Inheritance enables you to create new classes that reuse, extend, and modify the behavior defined in other classes.

How does Member inheritance work in C#? Does a class inherit all members of the base class?

        Interface declarations may define a default implementation for its members. These implementations are inherited by derived interfaces, and by classes that implement those interfaces.

        Example :  inheritance and can then inherit all the non-private members.

How does accessibility affect inheritance?

        public: The type or member can be accessed by any other code in the same assembly or another assembly that references it.
        private: The type or member can be accessed only by code in the same class or struct.
        protected: The type or member can be accessed only by code in the same class, or in a class that is derived from that class.

https://github.com/ThurberDaniel/burgerShack_cSharp
