# ISTA 322 ASP.Net MVC 5 Chapter 5 Homework
## Donovan Galloway
## 12 April 2018
1. What is a view engine? a piece of software that processes ASP.net content and looks for instructions, typically to insert dynamic content into the output sent to a browser.
2) What is Razor? the MVC Framework view engine.
3. What do views do? List two specific things in your answer to this question. The views exist to express one or more parts of the model to the user, such as HTML displaying data retrieved from one or more objects. It accept input and display output. 
4) How does Razor respond when it encounters statements that begin with the at character (@)? Be specific. The @model statement declares the type of the model object that will pass to the view from the action method. It evaluates what follows as code.
5. How does Razor respond when it encounters statements that begin with the at character followed by the colon (@:)? Be specific. It prevents Razor from interpreting it as C# statement, which is a default behavior when it encounters text.
6) Describe how you implement a standard formatting for all pages in an ASP.NET application. You specify lab.
7. What is the difference in using Razor to interpolate data values as stand-alone HTML elements and as attributes to HTML elements. What is the similarity? It detracts from the pattern of MVC.
8) What is a view start file and where is it located? It is used to automatically set the value 
9. What is a Razor code block? What is the syntax of a Razor code block? Located in the view.
10) Describe the different roles of action methods and views. The action method passes all the data to the view and the action method displays it.
11. Describe the use of the @using statement. Give an example of how you would use it. @using Razor.Models