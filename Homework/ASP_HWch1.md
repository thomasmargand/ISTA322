# Developing ASP.NET Web Apps Chapter 1 Homework
### Thomas Margand
### April 3, 2018

1. What year was ASP.NET introduced?

"2002". (pg1)

2. Briefly describe ASP.NET web forms.

A set of UI components (pages, buttons, etc) plus a stateful, object oriented GUI programming model. (pg1)

3. Briefly describe ASP.NET.

A way to host .NET applications in IIS (Microsoft's web server product) letting you interact with HTTP
requests and responses. (pg 1)

4. Briefly describe .NET.

A multi-language managed code platform (brand new at the time - a landmark in its own right). (pg1)

5. What is representational state transfer (REST)? This will take some independent research.

Representational State Transfer (REST) is an architecture style that is used for creating scalable
services. A RESTful Web Service is one that conforms to the REST architecture constraints. The
REST architectural style has quickly become very popular over the world for designing and architecting
applications that can communicate. Due to its simplicity, it has gained widespread acceptance worldwide
in lieu of the SOAP- and WSDL-based Web Services. It is essentially a client-server architecture and
uses the stateless HTTP protocol. (ASP.NET Web API by Joydip Kanjilal)

6. What is agile development? This will take some independent research.

Agile is a software development methodology that is becoming more popular every day. It defines the
mind set of many software development teams working across the globe. This article will walk you
through the entire Agile-scrum process and how, as a developer, you can contribute in an Agile way
and deliver value. Manifesto for Agile Software Development.

We are uncovering better ways of developing
software by doing it and helping others do it.
Through this work we have come to value:

Individuals and interactions over processes and tools
Working software over comprehensive documentation
Customer collaboration over contract negotiation
Responding to change over following a plan

That is, while there is value in the items on
the right, we value the items on the left more.
(https://www.c-sharpcorner.com/UploadFile/84c85b/agile-methodology-for-net-development-teams/)

7. What is unit testing?

Unit testing as a form of test driven development is the idea of designing software by describing
examples of desired behaviors as tests against which your software can be run. Unit testing tools
let you specify the behavior of individual classes or other small code units in isolation. These
can be effectively applied only to software that has been designed as a set of independent modules,
so that each test can be run in isolation. (pg 4)

8. What year was ASP.NET MVC introduced?
October 2007.

9. Describe URL routing. As part of your answer, discuss the concept of "clean URLs."

URL routing is a feature of ASP.NET MVC to provide clean URLs by default. This gives you control
over your URL schema and its relationship to your application, offering you the freedom to create a
pattern of URLs that is meaningful and useful to your users, without the need to conform to a
predefined pattern. Clean URLs referring to simple human readable URLs as compared to complex syntax
based ones. (pg 7)

10. What is the relationship between Microsoft's .NET platform and ASP.NET MVC?

First and most obviously, as ASP.NET MVC is based on the .NET platform, you have the flexibility to
write code in any .NET language and access the same API features - not just in MVC itself but in the
extensive .NET class library and the vast ecosystem of third party .NET libraries. Second, ready made
ASP.NET platform features such as authentication, membership, roles, profiles, and internalization can
reduce the amount of code you need to develop and maintain any Web application, and these features are
just as effective when used in the MVC framework as they are in a classic web forms project. (pg 7)

11. Chapter 1 does not discuss the MVC pattern specifically, and in a sense this entire course is an extended
examination of the MVC pattern. Using an independent resource briefly state the responsibility of (A) the model,
(B) the controller, and (C) the view.

The model is the central component of the pattern. It expresses the application's behavior in terms of the
problem domain, independent of the user interface. It directly manages the data, logic and rules of the
application. A view can be any output representation of information, such as a chart or a diagram. Multiple
views of the same information are possible, such as a bar chart for management and a tabular view for accountants.
The third part or section, the controller, accepts input and converts it to commands for the model or view.
(https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller#Components)
