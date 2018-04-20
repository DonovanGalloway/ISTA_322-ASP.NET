# ISTA 322 ASP.Net MVC 5 Chapter 3 Homework
## Donovan Galloway
## 8 April 2018
1. The book states, Interactions with an MVC application follow a natural cycle of user actions and view updates, where the view is assumed to be stateless." What does it mean for the view to be stateless? Web servers don't use any memory; every interaction between a user and web server has to contain all of the data
2) The book identifies two kinds of models. Briefly describe each of them. Model-View: represents data between views and controllers; Domain Model: single definition of the business data and processes within your application
3. Give an example of separation of concerns from your own life experience. This should be a simple, everyday example. 
4) What is a view engine? piece of code that takes input and produces output in HTML
5. The book notes that the three-tier structure, or n-tier model, is \the most widely used pattern for business applications." Why do you think that this is true? An answer like, Because it works well," is not a sufficient answer to this question. Uses a separation of concerns; separates the persistence code from the domain model and places it in a new component
6) This question requires some outside research. When we study UWP, you will see that the UWP design pattern is the Model-View-ViewModel (MVVM). What is the difference between MVC and MVVM that makes the first good for ASP.NET MVC and the second good for UWP? No control with the MVVM; you can create a variable on the view and maintain its state until its changed; you can't do that with HTTP
7. Describe the two parts of the dependency injection (DI) design pattern. To remove any dependency on a concrete class on a component; then inject the dependency on the class when you create the instance of it
8) Give an example of loose coupling from your own life experience. This should be a simple, everyday example. Leasing a car instead of buying so you're not tied down
9. What are the two types of testing discussed in the book? Unit Testing (testing each component) & Integration testing (all parts working together)
10) What are the seven steps of the test driven development (TDD) workflow, as stated in the book? 