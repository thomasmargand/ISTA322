# Developing ASP.NET Web Apps Chapter 3 Homework
### Thomas Margand
### April 11, 2018

1. The book states, “Interactions with an MVC application follow a natural cycle of user actions and view
updates, where the view is assumed to be stateless.” What does it mean for the view to be stateless?

A stateless protocol treats each request as an independent transaction that is unrelated to any previous request so that the communication consists of independent pairs of request and response.
(https://stackoverflow.com/questions/23470065/why-is-mvc-stateless-how-to-explain)

2. The book identifies two kinds of models. Briefly describe each of them.

Simple view models which just represent data being transferred between views and controllers or they can be domain models which contain the data in a business domain as well as the operations, transformations, and rules for manipulating that data. (pg 51)

3. Give an example of separation of concerns from your own life experience. This should be a simple,
everyday example.

Different aspects of life have different areas of concern that can be separate and apart from each other where one does not influence or affect the other, for example my financial obligations are separate and apart from my educational obligations.  My bills are still due at an appointed times regardless of when my school assignments are due, the two are not related and do no affect each other.

4. What is a view engine?

The component responsible for processing a view in order to generate a response for the browser. (pg 53)

5. The book notes that the three-tier structure, or n-tier model, is “the most widely used pattern for
business applications.” Why do you think that this is true? An answer like, “Because it works well,”
is not a sufficient answer to this question.

It has no constraints on how the UI is implemented and provides good separation of concerns without being too complicated. And, with some care, the DAL can be created so that unit testing is relatively easy. (pg 55)

6. This question requires some outside research. When we study UWP, you will see that the UWP design
pattern is the Model-View-ViewModel (MVVM). What is the difference between MVC and MVVM
that makes the first good for ASP.NET MVC and the second good for UWP?

One difference that people miss is in MVC, the controller chooses the view(ex. web server). After the view is chosen, the view's state isn't connected to the controller. MVVM, the state of the view is continuously connected to the ViewModel(has some features similar to the controller). Think WPF/datacontext.
(https://stackoverflow.com/questions/667781/what-is-the-difference-between-mvc-and-mvvm)

7. Describe the two parts of the dependency injection (DI) design pattern.

The first part is to remove any dependencies on concrete classes from the component, this is done by creating a class constructor that accepts implementations of the interfaces I need as arguments. The second part is to inject the dependencies. (pg 58)

8. Give an example of loose coupling from your own life experience. This should be a simple, everyday
example.

I write with my left hand.  Regardless of what I am writing or why I write the same way using my left hand.  When I need to write a note, or a check, or a letter I write using my left hand.  The reasons for and content of the writing are not related however they are loosely coupled to the method in which I write which is using my left hand.

9. What are the two types of testing discussed in the book?

The first is unit testing which is a way to specify and verify the behavior of individual classes (or other small units of code) in isolation from the rest of the application. The second type is integration testing, which is a way to specify and verify the behavior of multiple components working together, up to and including the entire web application. (pg 60)

10. What are the seven steps of the test driven development (TDD) workflow, as stated in the book?

 - Determine that you need to add a new feature or method to your application.
 - Write the test that will validate the behavior of the new feature when it is written.
 - Run the test and get a red light.
 - Write the code that implements the new feature.
 - Run the test again and correct the code until you get a green light.
 - Refactor the code if required.
 - Run the test to confirm that your changes have not changed the behavior of your additions.
 (pg 64)



Homework Notes

 - high cohesion, low coupling
