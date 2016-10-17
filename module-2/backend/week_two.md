## Week Two - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON - YOU are a web developer!!!). 

Note: When you're done, submit a PR. 

1. At a high level, what is ActiveRecord? What does it do/allow you to do?
  - Active Record is a database language that allows to create tables, records, and database objects that integrate with our Ruby programs. It provides us with methods and commands that allows us to relate and use these objects to display and manipulate data.

2. What kind of methods are `belongs_to`, and `has_many`? (i.e. class or instance) Give an example.
  - I believe they are instance methods that form the relationship of the objects in our programs.

3. What do they allow you to do?
  - belongs_to and has_many builds the relationship between DB objects and access those objects through separate but interconnected tables.

4. What's the difference between agile workflow and waterfall method?
  - Waterfall production starts with an idea and builds that idea out as effectively one iteration. The agile approach breaks a project up into smaller and more manageable pieces, giving us the ability to implement smaller iterations as we build it out. We can test specific parts of a project and make changes to the project more easily if we build it out methodically.

5. What is the difference between `#new` and `#create`?
  - New creates a DB object but will not save the object. Create builds the new object and saves it for us.

6. At a basic level, what does cURL allow you to do?
  - CURL allows us to send HTTP requests via the command line.

7. In a database that's holding students and teachers, what will be the relationship between students and teachers? Draw the schema diagram.
  - A student belongs_to a teacher and a teacher has_many students. Teacher - 'ID' / 'Name' Student - 'ID' / 'Name' / 'Foreign Key'

8. Define foreign key, primary key, and schema.
  - A foreign key is the ID of the data that relates to a DB object. The student table holds students, each student contains a foreign key that relates to a teacher, giving us the ID of their teacher. Each student also has a primary key that IDs the student within the student table. A schema outlines these relationships and provides us with the framework of our database design.

9. Describe the relationship between a foreign key on one table and a primary key on another table.
  - A foreign key on a table is the primary key on another. A teacher's ID is the foreign key in the student row on the student table.

10. What are the parts of an HTTP response?
  - The client sends a request to the server. The server responds to the request. The browser renders the appropriate data.

11. Describe some techniques to make our Sinatra code more DRY. Give an example of when you would use these techniques.
  - We can break out some controller language into a controller helper file.


### Optional Questions

1. Name your five favorite ActiveRecord methods (i.e. methods your models inherit from ActiveRecord) and describe what they do.
2. Name your three favorite ActiveRecord rake tasks and describe what they do.
4. What can you expect from a group as you begin working together? As you continue working together?
5. What two columns does `t.timestamps null: false` create in our database?
6. What cURL flag can you use to send a `POST` request?
7. What case does JSON (and JavaScript) use for multi-word variables?
8. What case does Ruby use for multi-word variables?
9. In a database that's holding schools and teachers, what will be the relationship between schools and teachers?
10. In the same database, what will you need to do to create this relationship (draw a schema diagram)?
11. Give an example of when you might want to store information besides ids on a join table.
12. Describe and diagram the relationship between patients and doctors.
13. Describe and diagram the relationship between museums and original_paintings.
14. What are some examples of acceptable values for the parts of an HTTP response?
15. What types of output do we want to test when we test our controllers?
16. What could you see in your code that would make you think you might want to create a partial?
17. Why might you use a helper method?
