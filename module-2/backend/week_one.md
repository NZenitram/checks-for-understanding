## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
-Put, Patch, Get, Post, Delete

2. What is Sinatra?
-A ruby platform that provides a localhost service and built in methods to assist with web app development.

4. What is MVC?
-Model, View, Controller programming principle. 

5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
-It makes them more readable and easier to understand. People who may need to read the code in the future will understand what was being done. 

6. What types of variables are accessible in our view templates without explicitly passing them?
-Instance variables.

7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    @count = 1
    name = 'Mr. Ed'
    'Some hash called locals here'
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed`?
9. What's the purpose of ERB?
-ERB allows us run Ruby on HTML pages. 

10. Why do I need a development AND test database?
-We use dev and test databases to more efficiently build out our programs and not destory or overwrite our real databases. 

11. What's responsive design?
-Responsive design is web design that is responsive to the screen size of the user. 

12. What is CRUD and why is it important?
-That is the thing.

13. What does HTTP stand for? 
-Hypertext Transfer Protocl

14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
-<%= %> <% %>

15. What's an ORM?
-Object Relational Mapping

16. What's the most commonly used ORM?
-Active Record

17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.
-Create-Post creates a new item, Create-Put updates an item, Read-Get allows us to access data, Update-Put modifies the current item, Update-Post does the same thing, Update-Patch and Delete- Delete

18. What's a migration? 
-The creation of or updating of a table within your database.

19. When you create a migration, does it automatically modify your database?
-No, you need to open the migration file and update the portions of the table you would like to change. 

20. How does a model relate to a database?
-The model is an object that acts as the "row" or store of data within a table. 
