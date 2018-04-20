# Programming in C# Chapter 18 Homework
### Thomas Margand
### April 16, 2018

1. You are building a help ticket system. You want to ensure that the older the ticket, the sooner it will
be handled by the team. For example, a ticket submitted a week ago has a higher priority than a
ticked just submitted. What kind of data structure would you use, and why?

I would implement the queue data structure because it employs a first in first out model which is the goal of the program in this instance.

2. You are building a tracking system for seasonal agricultural farm labor. The labor requirements vary
widely, depending on the season. Your requirement is that the newest hires are terminated first, and
that our more experienced hires are kept longer. What kind of data structure would you use, and why?

I would implement a stack data structure which employs a last in first out model which is the goal of the program in this instance.

3. You are building a transaction database. Your requirement is that the database adds data very quickly,
and that deletions, updates, and searches happen infrequently. In other words, data is typically added
in the order in which the transaction occurs. What kind of data structure would you use, and why?

I would implement a dictionary collection class because it creates an index to map to each element thus allowing for queries. It also has all the other required functionality.

4. You are building an analytical database. Your requirement is that the database handle queries very
quickly, but that the data never changes, i.e., there are no inserts, deletions, or updates. What kind
of data structure would you use, and why?

I would implement a dictionary collection class because it creates an index to map to each element thus allowing for queries. It also has all the other required functionality.

5. You are building a personnel directory, where searched are performed by last name, first name, middle
name. What kind of data structure would you use, and why?

I would use a sorted listed collection class because it allows the for assignment of keys to query by allowing for searches by last name, first name, or middle name.

6. You are building a username/password database. Your requirement is that updates happen frequently
(when users change their passwords) and that searches (to authenticate users) happen extremely
quickly. What kind of data structure would you use, and why?

I would use the HashSet collection class because it supports fast look ups and allows for cross checks by way of the IntersectWith, UnionWith, and ExceptWith methods.

7. What is a lambda expression? Give an example. Why would we use a lambda expression?

A lambda expression is an expression that returns a method an example is the find method.  I am not sure why you would use a lambda expression instead of a regular method call it is poorly explained in the text.

8. What is the difference between lambda expressions and anonymous methods? What are the advantages
of each?

Anonymous methods were added primarily, so that you can define delegates without having to create a named method-- you simply provide the definition of the method body in place of the method name. Lambda expressions provide a more succinct and natural syntax that anonymous methods, and they pervade many of the more advanced aspects of C#. (pg 415)
