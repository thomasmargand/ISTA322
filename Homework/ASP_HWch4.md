# Developing ASP.NET Web Apps Chapter 4 Homework
### Thomas Margand
### April 11, 2018

1. Using automatic properties is a shortcut that avoids several explicit steps. List the steps that the use
of automatic properties avoids.

Automatic properties skip the steps of defining the field or specifying the code in the getter and setter. (pg 71)

2. Using the object initializer syntax is a shortcut that avoids several explicit steps. List the steps that
the use of object initializers avoids.

The steps bypassed by using an object initializer are creating the object, setting the parameter values, and then calling the view method to display the result through the view. (pg 73)

3. What is the purpose of creating extension methods?

Extension methods are a convenient way of adding methods to classes that you do not own and cannot modify directly.     (pg 74)

4. What is the one feature of extension methods that will always allow you to identify a method as an
extension method?

The this keyword in front of the first parameter marks the method as an extension method. (pg 75)

5. How do you create an extension method that filters the results returned by the method on a user
specified criterion?

By using the yield keyword.

6. Explain the syntax of a lambda expression. The term “lambda expression” originates in the lambda
calculus developed by the mathematician Alonzo Church in the 1930’s. There is a class of programming
languages that are based on the fundamental ideas of lambda calculus.

The lambda expression is a concise format for expressing a method body in a delegate. It can be used to replace the delegation definition in the action method. The parameter is expressed without specifying a type, which will be inferred automatically. The => characters are read aloud as "goes to" and links the parameter to the results of the lambda expression. (pg 82)

7. This will require some outside research. What is the distinction between an anonymously typed variable
and a dynamically typed variable?

"The dynamic type is essentially object, but will resolve all method / property / operator etc calls at runtime via the DLR or other provider (such as reflection). This makes it much like VB with Option Strict Off, and makes it very versatile for calling into COM, or into DLR types. There is no type checking at compile time with dynamic; conversely, anonymous types are proper static-typed, type-checked beasts (you can see them in reflector, although they aren't pretty)." Additionally, anonymous types can be handled exclusively by the compiler; dynamic requires extensive runtime support - so anonymous types are a C# feature, but dynamic will largely be implemented by .NET 4.0 (with some C# 4.0 support).
(https://stackoverflow.com/questions/391529/anonymous-type-vs-dynamic-type)

8. You are having a discussion about C# with a friend of yours that uses another language. You are
telling him about C#’s LINQ library. How would you describe to him the difference between LINQ’s
SQL-like notation and LINQ’s dot notation?

The LINQ SQL like notation is exactly as it sounds a familiar SQL based syntax for querying data within C#. LINQ dot notation utilizes extension methods that have corresponding C# keywords. (pg 88)

9. What, exactly, does the await keyword do?

The await keyword tells the C# compiler that you want to wait for the result the selected method returns and then carry on executing other statements in the same method. (pg 94)

10. What is the connection between await and the async keywords?

When you use the await keyword you must also add the async keyword to the method signature. The await and async keywords are implemented using some clever compiler tricks, meaning that they allow natural syntax, but they do not change what is happening in the methods to which they are applied. (pg 94)
