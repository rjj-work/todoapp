# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation
- Each todo has:
  -- name
  -- description
- rails generate migration create_todos
```bash
gandalf15:todoapp rjj$ rails generate migration create_todos
Running via Spring preloader in process 33351
      invoke  active_record
      create    db/migrate/20180220020359_create_todos.rb

# edited file to add columns name & description

gandalf15:todoapp rjj$ rails db:migrate
== 20180220020359 CreateTodos: migrating ======================================
-- create_table(:todos)
   -> 0.0007s
== 20180220020359 CreateTodos: migrated (0.0007s) =============================
```

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

Start the servers
rail s -p 4000
