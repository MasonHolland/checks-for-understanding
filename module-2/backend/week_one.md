## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.

GET: find a particular page and return it, Read
POST: submit request, Create
PUT: edit or replace a particular item, Update
DELETE: delete a particular item, Delete
PATCH: edit or update a particular item, Update

2. What is Sinatra?

Sinatra is a DSL that works with active record and ruby. 

4. What is MVC?

Models, Views, Controller. Used as a model of how web apps should be built and how they work in rails. 

5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?

So that the transition to Rails is easier and so that our code is readable by the community. 

6. What types of variables are accessible in our view templates without explicitly passing them?\

params

7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    @count = 1
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?
```ruby
  get '/horses' do
    @count = 1
    @name = "Mr. Ed"
    erb :index
  end
  ```
9. What's the purpose of ERB?

It allows us to have and use ruby methods, variables and operations in a html file. 

10. Why do I need a development AND test database?

Test will work with a small group of data and help reduce test times so we are not iterating over the whole data set each time. Development allows us to check the whole dataset. 

11. What's responsive design?

It allows us to create webpages that will work on any device and can viewed and navigated just as easily on each. 

12. What is CRUD and why is it important?

Create, Read, Update, Delete
It gives us a framework for our users to edit the data and interact with it. 

13. What does HTTP stand for? 

Hyper Text Transfer Protocol

14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?

<%= %> this is for a single line no ruby
<% %> this is for a multi line operation

15. What's an ORM?

Object Relational Mapper

16. What's the most commonly used ORM in ruby (Sinatra & Rails)?

Active Record

17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.

Create: GET       This will take you to the page to create a new restaurant
Create: POST      This will "post" the newly created restaurant
Read:   GET       This will take you to the page of a single restaurant
Read:   GET       This will take you to the page listing all restaurants
Update: GET       This will take you to the page to edit a restaurant
Update: PUT       This will update the chosen restaurant
Delete: DELETE    This will delete a specific restaurant

18. What's a migration? 

A database operation that creates the framework that we will load data into.

19. When you create a migration, does it automatically modify your database?

You must run rake db:migrate to actually modify it. 

20. How does a model relate to a database?

It is what is referenced when looking at relationships between tables and creating validations for data. 

21. What's the difference between agile workflow and waterfall method?

Agile is taking an approach to work in iterations and complete a small portion of each aspect of the project. While waterfall is completing one section at a time before mocing on. 

22. What is the difference between `#new` and `#create`?

New will make it but will not save it to the database. Create will do that when it is made. 
