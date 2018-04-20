# Developing ASP.NET Web Apps Chapter 5 Homework
### Thomas Margand
### April 17, 2018

1. What is a view engine?

The component responsible for processing a view in order to generate a response for the browser. (pg 53)

2. What is Razor?

The Razor view engine processes the contents of views and generates HTML that is
sent to the browser. (pg 15)

3. What do views do? List two specific things in your answer to this question.

Views exist to express one or more parts of the model to the user and that means generating HTML that displays data that is retrieved from one or more objects. (pg 97) So they render views to user and also provide the layouts for how that view is rendered.

4. How does Razor respond when it encounters statements that begin with the at character (@)? Be
specific.

Prefixing with the @ symbol creates a razor expression that calls the Razor view engine. (pg 15)

5. How does Razor respond when it encounters statements that begin with the at character followed by
the colon (@:)? Be specific.

The @: characters prevent Razor from interpreting this as a C# statement, which is the default behavior whne it encounters text. (pg 114)

6. Describe how you implement a standard formatting for all pages in an ASP.NET application.

By using a layout.

7. What is the difference in using Razor to interpolate data values as stand-alone HTML elements and
as attributes to HTML elements. What is the similarity?

I have no idea. I don't really understand what this question is asking.

8. What is a view start file and where is it located?

A view start file is located in the \_ViewStart.cshtml and the contents will be treated as though they were contained in the view file itself and you can use this feature to automatically set a value for the Layout property. (pg 103)

9. What is a Razor code block? What is the syntax of a Razor code block?

A razor code block allows you to include C# statements in a view. The code block is opened with @{ and closed with } and the statements it contains are evaluated when the view is rendered. (pg 100)

10. Describe the different roles of action methods and views.

An action method passes a view model object to the view. A view uses the view model object to present content to the user. (pg 107)

11. Describe the use of the \@using statement. Give an example of how you would use it.

You can tidy up your views by applying the \@using expression to bring a namespace into context for a view, just like you would in a regular C# class. (pg 117)
