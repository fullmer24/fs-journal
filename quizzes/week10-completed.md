# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Difference between Structs and Classes: Struct are value types whereas Classes are reference types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
VOID
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
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
Type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Not having to have a complete implementation.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
To override the base class member in its derived class based on the requirement.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private, public, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
 Code in the same class or struct.
```