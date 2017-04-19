# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
to handle and hold the information so that it can relay it
to the front end to help interact with the client request.  example would be
client wants to read a data the backend would gather and send it to front end to
view
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
router
```

Which layer in the MVC pattern communicates with the model?

```md
the controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Views are merely puppets reading what the controller gives them.
```

What does C.R.U.D stand for?

```md
create read update destory
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
models
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
GET, POST, PATCH, DELETE
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
The router tells the controller what type of  GET it needs.  The controller then
talks to the model that handles that type of infomation.  Then the model pulls
for the database and sends it back to the controller.  The controller will then
send it to client to view
```

What is the command to generate a new rails-api app?

```bash
bin/rails new
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
bin/rake db:create, db:migrate, db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails generate scaffold Post name:string age:string
```
