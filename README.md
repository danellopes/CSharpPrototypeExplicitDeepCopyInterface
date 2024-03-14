### Example of the Prototype Design Pattern using an Explicit Deep Copy Interface

This example of the Prototype Design Pattern using an Explicit Deep Copy Interface pattern was develop using C# language.

The method for copying the object in this example consists of implementing an interface with a method called DeepCopy(), where it basically does the same job as the Copy Constructor, only this time it is explicit (as the title suggests). We still have the same problem where, if we’re dealing with dozens of types of objects, it would be necessary to implement this interface in every single class, making it repetitive and tedious.

If you're interested in the [udemy course](https://www.udemy.com/course/design-patterns-csharp-dotnet) by [Dmitri Nesteruk](https://www.udemy.com/user/dmitrinesteruk/).
