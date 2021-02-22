# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace in c# allows for multiple files to be using the same code.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A struct is a value type, and is copied on assignment. Classes are reference types and are garbage-collected.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The Static method.
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
it is an indication of the function's return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It is oreventing the car class from being instantiated. It is an incomplete class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It allows for the method to be overridden by any class that inherits it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal and protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
If a class or method is private, only the immediate block (namespace) that it is in has access to it.
```