# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
    Namespace is designed for providing a way to keep one set of names separate from another. The class names declared in one namespace does not conflict with the same class names declared in another.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
    Structs are value type whereas Classes are reference type.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
    Void returns a type and not a value.
```

## Example 1

```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```

**5.** In the example what is the access modifier of the `Start()` method?

<!-- enter you answer in the space below -->

```
    Public, which means it can be accessed.
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
    a data type
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
     abstract keyword enables you to create classes and class members that are incomplete and must be implemented in a derived class.Prevents it being instantiated.
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
    The virtual keyword is used to modify a method, property, indexer, or event declared in the base class and allow it to be overridden in the derived class.
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
      Public
      Private
      Protected
      Internal

```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
    Would you have to access it within the same class. I believe another term would be 'scoped'
```
