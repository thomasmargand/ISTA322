# Developing ASP.NET Web Apps Chapter 2 Homework
### Thomas Margand
### April 4, 2018

1. Describe what a controller does in the MVC design pattern.

The controller, accepts input and converts it to commands for the model or view.
In MVC architecture, incoming requests are handled by controllers. In ASP.NET MVC
controllers are just C# classes. (pg 15)

2. What is the ASP.NET MVC convention in naming controllers? What does
HomeController.cs do?

The MVC convention is to put controllers in the controllers folder, which
visual studio created when when it sets up a project. The class is called HomeController
and it is derived from the Controller class, which is found in the System.Web.Mvc namespace.

3. What is the name of the routing configuration file? Where is it located?

The routing configuration file is the Index method located in the HomeController class.

4. What is Razor? How does Razor treat an expression beginning with the (@) symbol?

The Razor view engine processes the contents of views and generates HTML that is
sent to the browser. Prefixing with the @ symbol creates a razor expression that
calls the Razor view engine.

5. How do view methods work?

The view methods call an object to which a viewbag property is assigned.  This allows
the passage of data from the controller to the view without having to define a
class beforehand.

6. What is the purpose of MVC models?

Well designed MVC applications start with a well designed model, which is then
the focal point as controllers and views are added.

7. What is a strongly typed view and why do we use strongly typed views?

A strongly typed view is intended to render a specific domain type, and if you
specify the type you want to work with MVC can create some helpful shortcuts to make
it easier. It is used because it offers conveniences and shortcuts to make coding easier.

8. What is the purpose of setting a start page URL?

So the program has a start point.

9. Describe the differences between HTTP GET and HTTP POST.

A GET request is what a browser issues normally each time someone clicks a link. This
version of the action will be responsible for displaying content. A POST request will be
responsible from receiving submitted data and deciding what to do with it.

10. Describe the two approaches to validation in web applications.

Client-side and server-side validation are the two different approaches.  Use client-side validation for optimum user experience and reduced network round trips, but always validate on the server for security reasons.
(https://msdn.microsoft.com/en-us/library/ee658099.aspx)

11. What is the role of cascading style sheets in web development?

Cascading style sheets create a stylized template for your page that prevent the programmer from having to manually code every piece of a page in HTML.  They allow for the more streamlined creation of a polished webpage or application.
