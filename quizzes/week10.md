# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace provides a scope to a group of related objects.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are reference types where structs are value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
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
The word public would be the access modifier of the Method Start().
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String is an indication that the function will return a string.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The word "Abstract" prevents the class from being instantiated.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The world virtual allows the method Start() to be overridden by an class that inherits it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Private, Protected, and Internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only instances of the same class. 
```