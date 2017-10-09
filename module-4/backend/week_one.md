## Week One - Module 4 Recap 

1. What's the most useful thing you learned from completing the intermission week work?

  Found it all to be incredibly usefull and found myself referring to them throughout the week. 
  
  
2. What are some tools to help debug JavaScript code?

  pryjs, debugger and Chrome's Dev Tools.


3. What are some tools you need in order to unit test your JavaScript?

  Mocha and Chai assertion library. NodeJS.
  
  
4. What is the syntax for invoking a function?

  functionName();
  
  
5. What's the difference between `==` and `===` in JavaScript?

  one will check to see if the data types are the same while the other will check that the values are equal
  
  
6. What's the difference between asynchronous and synchronous JavaScript? 

  synchronous waits for code to execute while asynchronous can continue to work while working on a process
  
  
7. What's a callback function and what are some reasons when we use/need callback functions?
  
  When we would like to continue running code and not wait.
  
8. What's the biggest difference between a promise and a callback?

  Unsure on this one. 
  Reasearch yielded that they are virtually the same, with callbacks performing every function a promise can. But combining promises is easier than callbacks. 
  
9. How do we setup a route when creating an API with Node and Express?
  AJAX.

10. What's `npm` and what do we use it for?

  Node Packet Manager
  To run and manage our packets. Serves a similar function as Bunlder in Ruby. 

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
  Models, Views, Controllers
  Models: The structure for an entity in the database. Dictates what variables are stored and what methods can be used on it. 
  Views: Dictates structure for the page and serves up the data to the client
  Controller: Uses the models to access the database and pass that information forward to the view. 
  

12. What is AJAX? What are some benefits of using AJAX?
  AJAX is Asynchronous Javascript and XML and it allows us to make API calls and retrieve other information without leaving or refreshing a page. 
  
  
13. What's a background worker? When would we want to use a background worker?
  A background worker allows us to set up a 'worker' who can take on a job and perform that operation while other code is being run and complete the work in the background. It allows for faster page loads as you can set up jobs in advance so computations are completed before they are needed. 
