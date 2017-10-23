## Week Three - Module 4 Recap

1. At a high level, what is Node?

A JavaScript runtime built on someones V8 engine. Allows us to write server side JavaScript. 

2. What is Express? What is Express similar to in the Ruby world?

Express is a framework for Node which allows us to create API's with far more ease. The equivalent in Ruby would be Rails.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

```app.get('/events', function (req, res) {
  res.send('GET all events endpoint.')
}```
  
  
4. What do we use Knex for?

We use Knex to interact with our database and help write readable queries.

5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?

Create a better routes layout and perhaps use multiple files for 'controller'. View and all visual related content should have been contained in a folder. Models were not utilized as much as they should have been. 

6. How do you execute raw SQL in node?

By using ```knex.raw(<passing in sql query here>).toSql```

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

Helps seperate logic and create pieces that can be developed seperately with ease. Can use differnt tools more suited to each piece instead of perhaps having to compromise by rolling them into one. 

Working in two apps can always cause unexpected problems. A breakdown in the chain is bound to happen at some point. Having to hit an external place to retrieve elements of a page could increase load times. 

#### Review  

8. Describe DNS.

No clue to be honest, don't remember ever having this mentioned in a class. I will add it to my list of things to research.

9. What does writing clean code mean to you?

Clean refactored code that is readable and dry with obvious clear intentions. Ideally any one can come in and understand what you are doing in each function/class/method. DRY code is also a big part of that. 

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?

A ruby application? I am unsure of how to take this quesiton. I will assume it is asking how I would do this in vanilla ruby if I distilled the problem. 

Classes:
Employee
Guest
Room
Transaction
