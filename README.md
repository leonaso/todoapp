# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version 2.3.3

* Rails version 5.0.0.1

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

- MVC
-Model, View, Controller

- Learn about CRUD -database operations
- C=Create, R=Read, U=Update, D=Delete

- What is a migration -create a table, update, delete operations.

- How to communicate with the database layer through models.

- Create a Todo model and routes
- Create a few Todo's objects in a rails console.

- Todo's:
-		Controller name: 	todos_controller, plural
-		Table name:	todos table, plural
-		Model name:	todo.rb, singular
-		class definition:	Todo, singular


- Creating Todos
	name: what kind of todos
	description: details of todos

	Initiate a new Todo object and save it to the database.

	.new -> creates a new object, but doesnt save it to the database
	.create -> will create and save to db if there are not errors.

	resources todos -> gives all the CRUD routes for todos.

	Read about routes and 0ne to many association

	Read about form_for helper

	Initiate a Todo instance variable 

	Flash: messages to flash to display errors or successful messages.


- Todo.find(params[:id])

	Version Control:
		git config --global <user.name> "my git user name"
		git config --global <user.email "myemail@domail.com"
		
		cd to application directory

Initialize repository:
	git init

Add files to repository
	git add -A

Check status
	git status

Commit to save your files	
	git commit -m "Initial commit comment"

	git push -u origin master	
		
-	CRUD databse operations completed from the browser's UI

- Create a partial to refactor code

-	Deploy to production

